Installation
------------
1. place `.vim`/`.vimrc` to Home direcotry:

* **Linux**:
```
$ git clone https://github.com/Why8n/dotfiles.git
$ cd dotfiles/vim
$ chmod +x ./bootstrap.sh
$ ./bootstrap.sh
```

* **Windows**:
```
$ git clone https://github.com/Why8n/dotfiles.git
$ cd dotfiles\vim
$ bootstrap.bat
```

2. open `vim`/`nvim`

3. open `vim`/`nvim`,type`:CocConfig`,and input below:
```
{
  // Enable preselect feature on neovim, default: `true`
  "suggest.enablePreselect": true,
  // Add preview option to `completeopt`, default: `false`
  "suggest.enablePreview": false,
  // completion automatically select the first completed
  "suggest.noselect": false,
  // "suggest.triggerAfterInsertEnter": true
  "suggest.minTriggerInputLength": 2,
  // trigger mode of auto completion: always(default),trigger,none
  "suggest.autoTrigger": "always",
  // support completion trigger on insert enter
  "suggest.triggerAfterInsertEnter": true,
  // Target to show hover information, default is floating window when possible.
  "coc.preferences.hoverTarget": "preview",
  // Auto close preview window on cursor move.,  default: `true`
  "coc.preferences.previewAutoClose": false
}
```
