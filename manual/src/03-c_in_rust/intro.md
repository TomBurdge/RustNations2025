# Working with C in Rust

It's *really* common to have some functionality in C that you want to use from Rust. It's *quite* common for this to be part of an effort to port the code over to Rust using a pattern like this:

1. Get the C linked in and working.
2. Write some unit tests to ensure that the C is doing what you think it's doing.
3. Write a Rust version, possibly line-by-line porting.
4. Run the same unit tests on the Rust version.
5. Stop using C, announce to the Ministry of Defence that your code is now safe, and roll around in a bathtub of money.
