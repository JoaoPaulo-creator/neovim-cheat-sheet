# neovim-cheat-sheet
 
rename a word/variable - :s/target/new_value <br />
        Ex.: :s/rain/sun <br />

rename all the occurrences - :%s/target/new_value/g <br />
    % denotes that the substitution should be applied to the entire file. <br />
    s stands for substitute. <br />
    target is the pattern you want to search for. <br />
    new_value is the replacement text. <br />
    g at the end stands for global, which means replace all occurrences on each line. If you omit g, only the first occurrence on each line is replaced. <br />

Vy - copy the hole line (yy work as well) <br />
=ap - format file



