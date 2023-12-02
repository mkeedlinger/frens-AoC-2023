# Day 02

To help keep things efficient at the North Pole, Santa uses a text intercom system to pass messages. But right now that system is bugging out! It isn't correctly decoding messages!

For this challenge, create a decoder for the following encoding scheme:

- Alphabetical characters are encoded as a 2 digit number with a prepended `\`
- `a` - `z` are encoded as 00 - 25
- `A` - `Z` are encoded as 26 - 51
- A `\` is escaped with `\\`
- Any other characters are left as is (the system Santa uses was made by elves, they hate latin characters so they encoded them)

There are two files: `small_message_encoded.txt`, which you can test on, and `large_message_encoded.txt`, which you should also decode and then share if you can hear "it" to prove you completed the challenge.
