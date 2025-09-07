# ddc-filter-sorter_lsp_kind

LSP kind sorter for ddc.vim

## Required

### denops.vim

https://github.com/vim-denops/denops.vim

### ddc.vim

https://github.com/Shougo/ddc.vim

## Configuration

```vim
call ddc#custom#patch_global('sourceOptions', #{
      \  lsp: #{
      \    sorters: ['sorter_lsp_kind'],
      \  }
      \})
```
