# llama-cpp-turboquant-mtp
llama-cpp branch, which also supports turboquant and mtp

This branch contains customized improvements based on **[llama\-cpp\-turboquant](https://github.com/QuinsZouls/llama-cpp-turboquant/tree/llama-next)**\.

All builds for this repository are **[release\-only](https://github.com/lemonyins/llama-cpp-turboquant-mtp/releases/new)**; no intermediate development builds are published\.

Load the MTP model, please execute the command: 

llama-server.exe  -m Qwen3.6-27B-MTP.gguf --spec-type mtp --spec-draft-n-max 2 --parallel 1 -c 61440 -ngl 999 --flash-attn on -ctk turbo4 -ctv turbo4
