Files are stored in the following directory:

\css
    \components\
      lqtxt-fields.less
    \global
      colors.less   # define colors
      reset.less    # standard DOM reset
      sizes.less    # padding and margin definition
      type.less     # font definition
      z-index.less  # z-index definition
    \prod
      lqtxt.css     #compiles CSS

Compile with the following

Install less @ the global using npm less -g
run the cmd compile:
lessc user.less prod/lqtxt.css;    
