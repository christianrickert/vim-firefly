# _Firefly_  🪲

![Artist's impression (ChatGPT, let's be real) of fireflies gathering at a forest clearing.](templates/firefly.png)

_Firefly_ is my personal dark vim color scheme with vibrant, but muted colors.

![Firefly's color palette.](templates/color-palette.png)

I got tired of looking at pea green strings with [gruvbox](https://github.com/morhetz/gruvbox) and created my own color scheme[^1]: Its color palette is tuned to reduce eye strain and help my brain process buggy source code late into the night, hence the name.
<br />
<table>
  <tr>
    <td align="center">24-bit color</td>
     <td align="center">8-bit color</td>
     <td align="center">4-bit color</td>
  </tr>
  <tr>
    <td align="center", valign="top"><img alt="Screenshot of the Firefly 24-bit color scheme with MacVim on maOS", src="templates/termguicolors.png"></td>
    <td align="center", valign="top"><img alt="Screenshot of the Firefly 8-bit color scheme with zsh on maOS", src="templates/t_Co%3D256.png"></td>
    <td align="center", valign="top"><img alt="Screenshot of the Firefly 4-bit color scheme with zsh on maOS", src="templates/t_Co%3D16.png"></td>
  </tr>
 </table>

_Firefly_'s color palette is optimized for Vim's `termguicolors`, but it adjusts seamlessly to reduced terminal colors (`t_Co=256`, `t_Co=16`). See the screenshots in the table above.

>[!TIP]
>You can install the firefly color scheme with [vim-plug](https://github.com/junegunn/vim-plug). Install the plugin manager and add these lines to your `vimrc`:
>```vim
>call plug#begin()
>
>" firefly - vim color scheme
>Plug 'christianrickert/vim-firefly'
>
>call plug#end()
>```

_I hope you will enjoy _Firefly_ as much as I do!_  🌙

[^1]: The color scheme files were generated with [vim-colortemplate](https://github.com/lifepillar/vim-colortemplate).
