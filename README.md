# libre-network-loader

A network/SD loader for the Wii.

If you make any changes to elf loading then you have to copy the updated `elf_loader.h` file from `elf_loader` to `source` to build the loader with it.

Configuration:
Change `payload_server` to the website you are hosting the payload on and `http_get_boot` to the GET request for the path of the file.

Building:
`make`

That's it!
