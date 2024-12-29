![Squeezed bug](header.jpg)

# Motivation
In this repository I investigating the potential of the buf visual studio code extension. It is expected that the extension will be capable of detecting all errors within proto files.

# Description
Read my [article](https://medium.com/@kinneko-de/792c1846a935) for the result.

<script src="https://gist.github.com/KinNeko-De/1dd97ac1ed63b2c2ec82d7b6d6bda016.js"></script>

# Structure
There are several samples with simple proto definitions. Each of these proto definitions has at least one error. I haeve grouped the samples by context:

| Sample | Context  |
|--------|----------|
| s0xx   | File     |
| s1xx   | Message  |
| s2xx   | Field    |
| s3xx   | Package  |
| s4xx   | Import   |
| s5xx   | Enum     |
| s6xx   | Oneof    |
| s7xx   | Repeated |
