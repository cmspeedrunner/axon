# Axon
This is the home repository for all the axon packages that can be installed for Tryptamine <br>
This is how your packages should be structured if you wish to contribute: <br>
You need to have a `.files` file under your root directory, for example, if we want to create a package called `hello`, with the main file being `hello.tryp`, this is how it would look: <br>
```
hello/
  .files
  hello.tryp
```
and your `.files` should look like this: <br>
**hello/.files** <br>
```
hello.tryp
```
Running `axon install hello` will now install `hello/hello.tryp` under the users std/ directory. To use your package, in this example you would do: <br>
```python
use "hello/hello"
# you could also do
use "hello/hello.tryp"
```
