# vm
Simple VM written in PHP inspired by Terrence Parr's talk "How to Build a Virtual Maschine"

https://www.youtube.com/watch?v=OjaAToVkoTw

# Usage

## Entry is top of sctipt
$ ./VM scripts/99.vms

## Entry is "main" label
$ ./VM scripts/fact.vms main

## Entry is "main" label, tracing on
$ ./VM scripts/print_array.vms main 1
