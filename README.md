<div align="center">

### ░▒▓█►─═ 𝕋ℍ𝔸ℕ𝕂𝕊 𝔽𝕆ℝ 𝕍𝕀𝕊𝕀𝕋𝕀ℕ𝔾! ═─◄█▓▒░


</div>

```
                            ░░░▒▒▓▓██████▓▓▒▒░░░
                       ░░▒▒▓▓██ ENES AYDIN ██▓▓▒▒░░
                            ░░░▒▒▓▓██████▓▓▒▒░░░
                              ___
                           .-'   `'.
                          /         \
                          |         ;
                          |         |           ___.--,
                 _.._     |0) ⚡(0) |    _.---'`__.-( (_.
          __.--'`_.. '.__.\    '--. \_.-' ,.--'`     `""`
         ( ,.--'`   ',__ /./;   ;, '.__.'`    __
         _`) )  .---.__.' / |   |\   \__..--""  """--.,_
        `---' .'.''-._.-'`_./  /\ '.  \ _.-~~~````~~~-._`-.__.'
              | |  .' _.-' |  |  \  \  '.               `~---`
               \ \/ .'     \  \   '. '-._)
                \/ /        \  \    `=.__`~-.
                / /\         `) )    / / `"".`\
          , _.-'.'\ \        / /    ( (     / /
           `--~`   ) )    .-'.'      '.'.  | (
                  (/`    ( (`          ) )  '-;
                   `      '-;         (-'
```

<div align="center">


```
█▀▀ █▄░█ █▀▀ █▀
██▄ █░▀█ ██▄ ▄█

▄▀█ █▄█ █▀▄ █ █▄░█
█▀█ ░█░ █▄▀ █ █░▀█
```

</div>


<p style="text-align: justify;">
  
I am Enes, I graduated from Computer Programming and I am currently studying Management Information Systems. With my interest and knowledge in software development processes, I aim to interact with the community by sharing my projects on the GitHub platform. I hope to both improve myself and inspire others by sharing what I have learned and experienced in this process. I also aim to further develop my skills by currently studying software at 42 Ecole. You can follow my work on GitHub and we can discover learning opportunities together.

Best regards,

</p3>


- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa
