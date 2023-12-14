# neovim-cheat-sheet

rename a word/variable - :s/target/new_value
        Ex.: :s/rain/sun

rename all the occurrences - :%s/target/new_value/g
    % denotes that the substitution should be applied to the entire file.
    s stands for substitute.
    target is the pattern you want to search for.
    new_value is the replacement text.
    g at the end stands for global, which means replace all occurrences on each line. If you omit g, only the first occurrence on each line is replaced.



