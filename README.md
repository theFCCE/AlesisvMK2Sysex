# AlesisvMK2Sysex
A python program to update settings on Alesis V49 MK2 midi keyboards using the sysext protocol 


Based information from Travis Mick reverse engineering of sysex
https://lo.calho.st/posts/reverse-engineering-sysex/
And with some code insperaction for the denationalization from his Alesis sysex tool https://github.com/tmick0/alesisvsysex

Unfortunately Alesis sysex implementation seems to have changed quit a bit when they went to the MK2 versions, so there is no backwards compatibility with previous Alesis keyboards. 
The code is based on the USB traffic i captured using a V49MK2. Would most likely work with V61MK2 as well with some minor modifications, but i don't have access to one so I can't test it.
