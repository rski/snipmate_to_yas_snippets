This repo contains the entirety of vim-snipmate snippets from
https://github.com/honza/vim-snippets/tree/master/snippets converted into
emacs yas snippets.

The snippets are converted using [snipmate_to_yas](https://github.com/cartolari/snipmate_to_yas).
They are updated and pushed daily by a cron job running on a RaspberryPi.

To use the snippets:

- Clone the repo:

    git clone https://github.com/rski/snipmate_to_yas_snippets

- Add the directory of the repo to the yas-snippets-dirs list:

    (add-to-list 'yas-snippet-dirs "/path/to/snippets/snipmate_to_yas_snippets")
