# Pi-Symmetric-Encoder

Objective:
Develop a Java program for symmetric file encoding, utilizing the digits of Pi (π) as keys to encode each byte of the input file. The encoding process involves using the first digits of Pi (3.14159265358979323846264338327950288419716939937510582097494459230781640628620), and when reaching the last digit (0), the sequence restarts with 3, 1, 4, and so on.

Key Steps:

Pi Digit Sequence:

Implement a mechanism to cyclically use the digits of Pi for encoding, ensuring that the sequence restarts when reaching the last digit (0).
File Encoding:

Read the input file byte by byte.
For each byte, apply a symmetric encoding operation using the corresponding digit from the Pi sequence.
File Decoding (Optional):

Provide an optional functionality to decode an encoded file using the reverse process, utilizing the Pi digits in the opposite order.
User Interaction:

Allow users to select the file for encoding and specify the output file for the encoded result.
Display clear messages and progress indicators during the encoding process.
Implementation Notes:

Use the digits of Pi as keys for encoding. When reaching the last digit (0), restart the sequence with 3, 1, 4, and so on.
Implement file I/O operations for reading the input file, encoding each byte, and writing the encoded result to an output file.
Testing:

Test the program with various input files, ensuring that the encoding and decoding (if implemented) processes are accurate.
Verify the cyclic usage of Pi digits for encoding by examining the encoded output.
Assess the program's performance and correctness for different file sizes and content types.
Note:

Due to the transcendental nature of Pi, it is not feasible to use its exact digits for encoding. Instead, a truncated sequence of digits should be used for practical implementation.
