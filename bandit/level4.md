# Level 4

## Chal

The password for the next level is stored in a hidden file in the inhere directory.

## Explanation

hidden files contain "." (dot) at the front of their names

`ls -la` -- -l: use long listing format, -a: don't ignore entries starting with .

## Solution

command:

```sh
cd inhere
ls -la
cat ...Hiding-From-You
```

password: `2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ`
