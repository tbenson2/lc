# Code:

## Section A (Rhythmic, Acoustic)
    stack [
    s "cpluck*3" # n (irand 15),
    s "flbass*8" # n (irand 17) # speed "<1 1.3 2>",
    jux rev $ s "cpluck*4" # n (irand 15) # speed "< 5 4 3 >"
    ]

## Section B (Ambient, Creepy)
    stack [
    jux rev $ s "newnotes*68" # n (irand 15) # speed "<6 5 3>" # gain 0.6,
    jux rev $ s "noise2*2" # n (irand 8) # speed sine # gain 0.9,
    s "pad*1" # n (irand 5) # speed "<0.5 0.6 0.7>",
    jux rev $ slow 2 $ s "alphabet*26" # n (irand 26) # speed (-2) # gain 0.6 # cutoff (2000)
    ]

Overall this project was really fun, and I truly enjoyed working with Ken, Helen, and Dante. The first day Helen was not there, and we spent the first few minutes saying "so......." to each other without any real direction. Once Helen joined us the week after, she took on a bit of an organizational leadership role, which really helped us get going. I was in charge of doing melodies, and at the start I was stumped as to what sounds I should use. But after some perusing around, I settled on `cpluck` and `flbass`, two nice bass sounds with good variety that went together nicely. `cpluck` especially went very well with Dante's printer and coffee sounds, and it created a more acoustic clockwork feel that I really enjoyed. After playing with that for a while, we naturally switched to a more ambient, experimental approach. Here `jux rev` was my friend, and I also learned that playing with the speed of a sound can drastically change the character of it into something more interesting (potentially). For example, `newnotes` as they are are pretty pedestrian, just some sine blips. But playing them rapidly and at 5 or 6 times their normal speed, they turned into a nice sparkly glitchy texture up top.

Our group got together for a couple hours on Wednesday to run through what we had, and boy am I glad we did that! Our transition from section A to B was not nearly fast enough, we let the pace stagnate quite a bit while we were trying to figure things out, and overall the piece definitely needed some tightening up. By the end of those couple hours, we all knew what we needed to do to get the piece sounding right. And I'm pleased to say, the performance went off without a hitch in my opinion! I felt like we were all connected and listening, and keeping the pace up so nothing got too boring. Overall I'm extremely happy with the way it turned out.