## Usage

```TextGenerator <prefix_length> <num_characters>```

* `prefix_length`:The length of the prefix to be used for text generation. The higher the value, the more likely it is to directly copy from the given texts. Recommended values are between 4-8, with the sweet spot being at around 6-7 in my experiences
* `num_characters`: Number of characters to generate

The program will sample from texts in the folder `Source Texts/`. Any file can be used in here to sample but I recommend plaintext files. Paste as many as you want. Keep in mind longer text files will generally have "priority," meaning you'll be much less likely to see content from smaller text files as opposed to huge ones like movie scripts and such.

## Sample

### Source texts

* `F14Wiki.txt`: Wikipedia page of the F14 Tomcat naval multirole fighter jet
* `shrek.txt`: The entire script of Shrek
* `Yujiro.txt`: Yujiro Hanma wiki

### Parameters

* `prefix_length = 6`
* `num_characters = 250`

### Output

```
y I can fly! -He can talk! -Ha, ha! {Shrek sighs} -What? Oh, man, believe I'm a little without his finger and F/A-18E/F Super Hornet entering sexual connotation and high-speed of his hard to six Phoenix missiles led to the sweep during them, as heck ain't
```
