# Extended Functions

Pure-GML extended functions and methods for Game Maker Studio 2 projects.

### Contents

```
string_explode("delimiter", "string");
 // Explode a string into an array ( "a;b;c" -> [a, b, c] )
array_implode("glue", array);
 // Paste together an array into a  string ( [1, 2, 3] -> "1;2;3" )
string_reverse("string");
 // Reverse -> esreveR
string_mask("string");
 // Password -> ********
url_encode("url");
 // "test for # url?" -> "test%20for%20%23%20url%3F"
url_decode("encoded_url");
 // "test%20for%20%23%20url%3F" -> "test for # url?"
dectohex(number);
 // 123 -> "7B"
hextodec("hex string");
 // "7B" -> 123
string_ends_with("haystack", "needle");
 // string_ends_with("Testing", "ing") -> True
string_starts_with("haystack", "needle");
 // string_starts_with("##A Test", "#") -> True
string_prepend(string, prependchar, length); // Prepend a string to a set length
 // string_prepend('123', '0', 5) -> 00123
string_append(string, appendchar, length); // Append a string to a set length
 // string_append('123', 'ABC', 7) -> 123ABCA
round_whole(number, round); // Round number on big numbers. 
 // round_whole(1234, 10) = 1230
netevent_to_string(event); // Get a string representation of the network async events
 // netevent_to_string(network_type_non_blocking_connect) = "non-blocking connect"
bit_from_byte(byte, bitnr); // Get a bit at position from a number
 // bit_from_byte(1, 0); // returns 1 - (first bit is 1, rest is 0)
string_trim(string); // Trim the string of surrounding whitespaces
 // string_trim("   trim   me    "); // returns "trim   me"
extract_header_from_string(string); 
 // Returns an array of headers (key=>value) from a HTTP formatted response (RFC 2616)
debug_log(string); 
 // Debug output with time and instance information
```
