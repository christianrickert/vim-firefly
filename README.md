# firefly
Firefly - Vim Color Scheme

![Artist's impression (ChatGPT, let's be real) of fireflies gathering at a forest clearing.](templates/firefly.png)

My personal dark Vim color scheme.

I got tired of looking at pea green strings with [gruvbox](https://github.com/morhetz/gruvbox) and created my own color scheme that is easy on the eyes: It exhibits a muted color palette that reduces eye strain and helps my brain to process source code late into the night, hence the name.

The color palette is optimized for Vim's `termguicolors`, but it adjusts seamlessly to reduced terminal colors (`t_Co=256`, `t_Co=16`). See screenshots for comparison:
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

>[!TIP]
>You can install the Firefly color scheme with [vim-plug]() by adding these lines to your `vimrc`:
>```vim
>call plug#begin()
>
>" Firefly - Vim Color Scheme
>Plug 'christianrickert/vim-firefly'
>
>call plug#end()
>```

The color scheme files were generated with [vim-colortemplate](https://github.com/lifepillar/vim-colortemplate).
