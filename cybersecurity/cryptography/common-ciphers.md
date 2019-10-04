# Common Ciphers

### Caesar Cipher

Given Message

```text
Hello World
```

You shift the letters of the alphabet 

![Caesar Cipher Shift 3](../../.gitbook/assets/ccipher.png)

Now you have a table , according to the table above A = D, D = G, and so forth.

So now:

```text
Hello world :: Plaintext
Khoor zruog :: Cipher Text
```

### Vigenère Cipher

Given the same text

```text
Hello World
```

So now we have this Vigenère Square

![Vigen&#xE8;re Square](../../.gitbook/assets/vcipher.png)

With this now we make up a key

```text
key = script
```

Now we make the key the same number of letters as the plaintext and then following the square find the letters matching for example "F" and "G" would turn into "L"

```text
HelloWorld :: Plaintext
ScriptScri :: Key
zgctdpgtcl :: Ciphertext
```

