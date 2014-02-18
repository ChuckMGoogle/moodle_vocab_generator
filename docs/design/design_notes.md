# Design Notes

## References
"GIFT Format". [docs.moodle.org/23/en/GIFT_format](docs.moodle.org/23/en/GIFT_format)

## Output Files
The program will produce the following GIFT-formatted output file types:

	* Fill in the Blank
	* Word Match

### Fill in the Blank

The Fill in the Blank quiz type provides a sample question that has a short definition of the correct word enclosed in parentheses. The point where the word is inserted in the sentence is marked by using an open curly brace ('{') immediately followed by a closing curly brace ('}'). The list of possible words appears between the curly braces and are separated by a newline character. It is strongly advised that each sample sentence end with a period.

### Word Match

The Word Match quiz type provides a list of words and definitions in the form of a single "question" entry" with multiple answers that derive an aggregate score.



