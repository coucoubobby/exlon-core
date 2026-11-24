Check https://sites.google.com/view/exlon-compute for a deeper overview.

Model's are not GGUF and not standard, so they need to have their own .c loader.
hrwi-cli and hrwi-server are coming in .c files that can be then compiled using cc.
No prebuilt binary, the code will be small.

models come in .hruf (HRWI Universal Format, a nod to GGML Universal File)
