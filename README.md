coolbasic-sublime-syntax
========================

Syntax file sources for sublime text. 
Compile on sublime text 3 by pressing ctrl+b and place the resulting file in sublime-text-3/Packages/User/

Use a build system similar to this in combination for the best experience:

    {
        "shell_cmd": "cd ~/git/CBCompiler/bin/ && ./CBCompiler $file && ./cbrun",
        "selector": "source.cb_compiled"
    }

Based on https://github.com/pettis/coolbasic-pygments 
