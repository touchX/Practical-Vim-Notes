Practical-Vim-Notes
===================

#Content

##1.The Vim Way
Tip 1. [Meet the Dot Command](tip1.md): `.`, `x`, `u`, `dd`, `>G`, `i`, `<Esc>`  
Tip 2. [Don’t Repeat Yourself](tip2.md): `$`, `a`, `A`  
Tip 3. [Take One Step Back, Then Three Forward](tip3.md): `f{char}`, `s`, `;`   
Tip 4. [Act, Repeat, Reverse](tip4.md): `F{char}/T{char}`, `/pattern<CR>`, `:s/target/replacement`  
Tip 5. [Find and Replace by Hand](tip5.md): `/target`, `*`, `*nn`, `cw`  
Tip 6. [Meet the Dot Formula](tip6.md): **One key to move, One key to execute**

Part I — Modes  
##2. Normal Mode  
Tip 7. [Pause with Your Brush Off the Page](tip7.md)  
Tip 8. [Chunk Your Undos](tip8.md)  
Tip 9. [Compose Repeatable Changes](tip9.md)  
Tip 10.[Use Counts to Do Simple Arithmetic](tip10.md)  
Tip 11.[Don’t Count If You Can Repeat](tip11.md)  
Tip 12.[Combine and Conquer](tip12.md)  
##3. Insert Mode  
Tip 13. Make Corrections Instantly from Insert Mode  
Tip 14. Get Back to Normal Mode  
Tip 15. Paste from a Register Without Leaving Insert Mode  
Tip 16. Do Back-of-the-Envelope Calculations in Place  
Tip 17. Insert Unusual Characters by Character Code  
Tip 18. Insert Unusual Characters by Digraph  
Tip 19. Overwrite Existing Text with Replace Mode
##4. Visual Mode
Tip 20. Grok Visual Mode  
Tip 21. Define a Visual Selection  
Tip 22. Repeat Line-Wise Visual Commands  
Tip 23. Prefer Operators to Visual Commands Where Possible  
Tip 24. Edit Tabular Data with Visual-Block Mode  
Tip 25. Change Columns of Text  
Tip 26. Append After a Ragged Visual Block  
##5. Command-Line Mode
Tip 27. Meet Vim’s Command Line  
Tip 28. Execute a Command on One or More Consecutive Lines  
Tip 29. Duplicate or Move Lines Using ‘:t’ and ‘:m’ Commands  
Tip 30. Run Normal Mode Commands Across a Range  
Tip 31. Repeat the Last Ex Command  
Tip 32. Tab-Complete Your Ex Commands  
Tip 33. Insert the Current Word at the Command Prompt  
Tip 34. Recall Commands from History  
Tip 35. Run Commands in the Shell  
Part II — Files  
##6. Manage Multiple Files
Tip 36. Track Open Files with the Buffer List  
Tip 37. Group Buffers into a Collection with the Argument List  
Tip 38. Manage Hidden Files  
Tip 39. Divide Your Workspace into Split Windows  
Tip 40. Organize Your Window Layouts with Tab Pages  
##7. Open Files and Save Them to Disk
Tip 41. Open a File by Its Filepath Using ‘:edit’  
Tip 42. Open a File by Its Filename Using ‘:find’  
Tip 43. Explore the File System with netrw  
Tip 44. Save Files to Nonexistent Directories   
Tip 45. Save a File as the Super User   
Part III — Getting Around Faster  
##8. Navigate Inside Files with Motions
Tip 46. Keep Your Fingers on the Home Row   
Tip 47. Distinguish Between Real Lines and Display Lines   
Tip 48. Move Word-Wise   
Tip 49. Find by Character   
Tip 50. Search to Navigate   
Tip 51. Trace Your Selection with Precision Text Objects   
Tip 52. Delete Around, or Change Inside   
Tip 53. Mark Your Place and Snap Back to It   
Tip 54. Jump Between Matching Parentheses   
##9. Navigate Between Files with Jumps
Tip 55. Traverse the Jump List   
Tip 56. Traverse the Change List   
Tip 57. Jump to the Filename Under the Cursor   
Tip 58. Snap Between Files Using Global Marks   
Part IV — Registers  
##10. Copy and Paste
Tip 59. Delete, Yank, and Put with Vim’s Unnamed Register   
Tip 60. Grok Vim’s Registers   
Tip 61. Replace a Visual Selection with a Register   
Tip 62. Paste from a Register   
Tip 63. Interact with the System Clipboard   
##11. Macros
Tip 64. Record and Execute a Macro   
Tip 65. Normalize, Strike, Abort   
Tip 66. Play Back with a Count   
Tip 67. Repeat a Change on Contiguous Lines   
Tip 68. Append Commands to a Macro   
Tip 69. Act Upon a Collection of Files   
Tip 70. Evaluate an Iterator to Number Items in a List   
Tip 71. Edit the Contents of a Macro   
Part V — Patterns
##12. Matching Patterns and Literals
Tip 72. Tune the Case Sensitivity of Search Patterns   
Tip 73. Use the \v Pattern Switch for Regex Searches   
Tip 74. Use the \V Literal Switch for Verbatim Searches   
Tip 75. Use Parentheses to Capture Submatches   
Tip 76. Stake the Boundaries of a Word   
Tip 77. Stake the Boundaries of a Match   
Tip 78. Escape Problem Characters   
##13. Search
Tip 79. Meet the Search Command   
Tip 80. Highlight Search Matches   
Tip 81. Preview the First Match Before Execution   
Tip 82. Count the Matches for the Current Pattern   
Tip 83. Offset the Cursor to the End of a Search Match   
Tip 84. Operate on a Complete Search Match   
Tip 85. Create Complex Patterns by Iterating upon Search History   
Tip 86. Search for the Current Visual Selection   
##14. Substitution
Tip 87. Meet the Substitute Command   
Tip 88. Find and Replace Every Match in a File   
Tip 89. Eyeball Each Substitution   
Tip 90. Reuse the Last Search Pattern   
Tip 91. Replace with the Contents of a Register   
Tip 92. Repeat the Previous Substitute Command   
Tip 93. Rearrange CSV Fields Using Submatches   
Tip 94. Perform Arithmetic on the Replacement   
Tip 95. Swap Two or More Words   
Tip 96. Find and Replace Across Multiple Files   
##15. Global Commands
Tip 97. Meet the Global Command   
Tip 98. Delete Lines Containing a Pattern   
Tip 99. Collect TODO Items in a Register   
Tip 100. Alphabetize the Properties of Each Rule in a CSS File   
 Part VI — Tools  

##16. Index and Navigate Source Code with ctags
Tip 101. Meet ctags   
Tip 102. Configure Vim to Work with ctags   
Tip 103. Navigate Keyword Definitions with Vim’s Tag Navigation Commands   
##17. Compile Code and Navigate Errors with the Quickfix List  
Tip 104. Compile Code Without Leaving Vim   
Tip 105. Browse the Quickfix List   
Tip 106. Recall Results from a Previous Quickfix List   
Tip 107. Customize the External Compiler   
##18. Search Project-Wide with grep, vimgrep, and Others  
Tip 108. Call grep Without Leaving Vim   
Tip 109. Customize the grep Program   
Tip 110. Grep with Vim’s Internal Search Engine   
##19. Dial X for Autocompletion
Tip 111. Meet Vim’s Keyword Autocompletion   
Tip 112. Work with the Autocomplete Pop-Up Menu   
Tip 113. Understand the Source of Keywords   
Tip 114. Autocomplete Words from the Dictionary   
Tip 115. Autocomplete Entire Lines   
Tip 116. Autocomplete Filenames   
Tip 117. Autocomplete with Context Awareness 
##20. Find and Fix Typos with Vim’s Spell Checker
Tip 118. Spell Check Your Work   
Tip 119. Use Alternate Spelling Dictionaries   
Tip 120. Add Words to the Spell File   
Tip 121. Fix Spelling Errors from Insert Mode   
##21. Now What?
21.1 Keep Practicing!   
21.2 Make Vim Your Own   
21.3 Know the Saw, Then Sharpen It   
