# Cyber Security Challenge 2015: Reverse That Binary

**Category:** Reverse Engineering
**Points:** 20
**Description:**

> We received a binary that guards a flag. However, the password has been lost. Can you still retrieve the flag?
>
> [`login`](login)

## Write-up

Running 'file login' in Linux tells you it's an ELF 64-bit (64-Bit Linux executable).
Running 'strings login' in Linux tells you the strings (cleartext code) in the binary, you will find this:
impo
ssib
le_t
o_gu
ess_
pass
word

With below that:
Flag: You_hacked_it

To verify, just run it and enter the password 'impossible_to_guess_password'
Flag: [`You_hacked_it`]You_hacked_it


## Other write-ups and resources

* none yet
