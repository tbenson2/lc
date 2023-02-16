## Patch:

    stack [
    jux rev $ n (scale "minPent" "0 1 2 3 4") # s "subroc3d*5" # vowel "a e i o u" # gain 0.8
    , s "reverbkick*2" # gain 0.9 # cutoff 2000
    , s "~ ~ ~ ~ ~ ~ [sd, cp] ~ ht? ~" # n (irand 2) # gain 1.05
    , jux rev $ s "[noise2 noise2 hh27 noise2 noise2]*2" # n (irand 13) # gain 1.1
    ]

## Documentation:

This week I got super inspired and watched a ton of TidalCycles pieces performed by members of the live coding community, including Alex McLean and Antonio Roberts. Most of what I saw them do, I had absolutely no idea what it was they were doing exactly. But after a week of watching this stuff, I'm starting to get a little bit of a handle on the syntax. I think that'll be super helpful when it comes time for the Tidal unit of this class.

One of the things I learned from Alex is that `jux rev` is a magical thing :)

I also jammed with @cleary from the Estuary discord channel this past weekend, and that was immensely helpful to get a hold on things. I learned how to comment lines out on the fly and bring them back in, as well as just getting more experience using MiniTidal. It was very helpful and [extremely fun!](https://www.youtube.com/watch?v=cCrAWhQaDIk&t=1436s) 

For this particular patch, it ended up being in 5/4. I decided to use the minPent scale (which has 5 notes) on the `subroc3d` pack (which has 5 samples in it). Then I put a `vowel` filter, sweeping through all 5 vowels each cycle. So yeah, a lot of 5s. I used a `cutoff` to rein in the kick drum sample, and I used the magical `jux rev` on the main riff and the hihats to add some spice and stereo-icity. You'll notice that I've decided to put a comma at the beginning of each line in the stack instead of at the end. This is so I don't have to think about adding or removing commas if I decide to comment out certain lines during a performance. A lot of the errors I got, especially during my jam with cleary, were "Parse Error"s, which just meant there were commas where there weren't supposed to be, or there was a missing comma somewhere. I came up with this "comma first" system just now, and I'm so glad it works!