# CaesarCipher

The Caesar cipher involves replacing each letter in a message with the letter that is a certain number of letters after it in the alphabet. So, in an English message, we might replace each A with D, each B with E, each C with F, and so on, if shifting by three characters. We continue this approach all the way up to W, which is replaced with Z. Then, we let the substitution pattern wrap around, so that we replace X with A, Y with B, and Z with C.


This repository contains an algorithm for solving  for the Caesar
cipher technique.

Sample Test
```
cipher = CaesarCipher(3)
message = "THE EAGLE IS IN PLAY; MEET AT JOE'S"
coded = cipher.encrypt(message)
print("Secret: ", coded)
answer = cipher.decrypt(coded)
print("Message: ", answer)
```

Sample Output:
```
Secret:  WKH HDJOH LV LQ SODB; PHHW DW MRH'V
Message:  THE EAGLE IS IN PLAY; MEET AT JOE'S
```
