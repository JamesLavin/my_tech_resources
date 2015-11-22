
INSERT MODE COMMANDS
<C-n>              autocomplete
<C-d>              ???

COMMAND MODE COMMANDS
<Leader><Enter>    insert line below without switching to insert mode
<Leader>u          insert line above without switching to insert mode
<C-]>              open tag in vertical split
<C-c>              ???
<C-n>              toggle NERDTree
<C-h>              move to window on left
<C-j>              move to window below
<C-k>              move to window above
<C-l>              move to window on right
:Ag                ag search
  o/Enter            open
  e                  open & close quickfix window
  t                  open in tab
  v                  open in vertical split
  q                  close quickfix

TAGS
K
:ta {name}         jump to tag
:ta /^before_*     jump to tag
<Leader>T          jump to tag in new tab
<Leader>.          browse tags using Ctrl-P
  <C-t>              open tag in new tab
  <C-]>              open tag in vertical split
<C-T>              return from tag (back button)
:ts {name}         list tags
  :{n}tn             jump to next matching tag
  :{n}tp             jump to prev matching tag
:h tags            help

LEADER COMMANDS
<Leader><Leader>   jump back-and-forth between files (in same window)
<Leader>]          jump to next tab
<Leader>[          jump to prev tab
<Leader>a          run all specs
<Leader>ag         ag search, then open in vertial split
<Leader>f          go to file in vertical split
<Leader>l          re-run last spec
<Leader>m          move current window to new tab
<Leader>nc         :RTcontroller
<Leader>nf         :RTfunctionaltest
<Leader>nh         :RThelper
<Leader>ni         :RTintegrationtest
<Leader>nj         :RTjavascript
<Leader>nl         :RTlayout
<Leader>nm         :RTmodel
<Leader>ns         :RTspec
<Leader>nv         :RTview
<Leader>nu         :RTunittest
<Leader>o          :TagbarToggle for "(o)verview"
<leader>rc         open .vimrc in vertical split
<Leader>s          RunNearestSpec
<Leader>t          RunCurrentSpecFile
<Leader>T          jump to tag in new tab
<Leader>vc         :RVcontroller<CR>
<Leader>vf         :RVfunctionaltest<CR>
<Leader>vh         :RVhelper<CR>
<Leader>vi         :RVintegrationtest<CR>
<Leader>vj         :RVjavascript<CR>
<Leader>vl         :RVlayout<CR>
<Leader>vm         :RVmodel<CR>
<Leader>vs         :RVspec<CR>
<Leader>vv         :RVview<CR>
<Leader>vu         :RVunittest<CR>
<Leader>w          <C-w>w
<Leader>we         <C-w>=
<Leader>x          open eXtra tab

COMMAND MODE COMMANDS
~                  toggle case
.                  repeat last command
<C-r>              redo an undo
a                  append after cursor
A                  append after line
d{motion}          delete text that {motion} moves over
D                  delete to end of line
dd                 delete line
gI                 insert at start of line
i                  insert before cursor
I                  insert before first non-blank in line
K                  search for word under cursor
  <Ctrl-W><CR>       Open file/line in a new window
  <Ctrl-W>T          Move the new window to a new tab
o                  open line below (and switch to insert mode)
O                  open line above (and switch to insert mode)
r                  replace character
R                  switch to insert mode but replace characters
u                  undo
v                  switch to visual mode
V                  switch to visual linewise mode
x                  delete
X                  backspace
:[range]d          delete lines
:[range]s/{pattern}/{string}/c
                 c = confirm; i = ignore case; g = replace all occurrences in line
:noh               turn off search highlighting

COMMAND MODE MOVEMENT COMMANDS
0                  move to beginning of line
$                  move to end of line
^                  move to first non-blank space
b                  backward a word
f{char}            forward to (and including) {char} (F goes backwards)
gg                 goto first line
t{char}            till before {char} (T goes backwards)
{n}G               goto line {n}
:{n}               goto line {n}
w                  forward a word
;                  repeat last f, t, F, T  (, repeats backwards)

TABS
:tabe              edit in new tab
:tabclose          close tab
:tabm n            move tab to position n
:tabm +n           move tab right n positions
:tabm -n           move tab left n positions

FILES
:e(dit)            edit file
:e(dit)!           reload file and edit
:r(ead)            insert file below cursor
:r(ead) !{cmd}     execute {cmd} and insert std output below cursor
gf                 goto file under cursor
<Leader>f          goto file in vertical split
<C-w>f             goto file under cursor in new window
<C-w>gf            goto file under cursor in new tab

REGISTERS
"ay{motion}        yank text that {motion} moves over & put in register a
  "ay$               yank till end of line & put in register a
"ad{motion}        delete text that {motion} moves over & put in register a
"a{n}yy{motion}    yank next {n} lines & put in register a
{visual}"ay        yank highlighted text into register a
:[range]y a        yank [range] lines into register a
:reg               display registers
:reg a             display registers with "a" in their names
"ap                paste register a after cursor

VISUAL MODE COMMANDS
~                  toggle case
d                  delete
c                  change
y                  yank
>                  shift right
<                  shift left
!                  filter through external command

WINDOWS
<C-w>T             break current window into new tab
<C-w>r             rotate windows
<C-w>x             swap window with next
<C-w>|             maximize width
<C-w>=             equalize width
<C-w>H             move window to far left
<C-w>L             move window to far right
<C-x>              move current window to new tab
<C-=>              equalize window size

BUFFERS
:ls                list buffers
:only              only keep open current buffer
gn                 goto next buffer (:bn<CR>)
gp                 goto prev buffer (:bp<CR>)

NERDTREE
<C-n>              toggle NERDTree
I                  toggle display of hidden files
?                  display commands
p                  parent
r                  refresh
s                  open in new split window
t                  open in new tab
x                  close node parent

HELP
:h keycodes        display special keycodes
:h windows         windows help

CTRL-P
<C-p>              fuzzy file search
  <C-v>              open in vertical split
  <C-t>              open in tab

JUMPS
:jumps .           list visited files
<C-o>              jump backward
<C-i>              jump forward

BUNDLER
:Bundle open {gem} open gem
gem pristine {gem} restore original

FUGITIVE
:Gstatus           show Git status
  p                  add/reset --patch
  -                  add/reset file's changes
:Gwrite            git add current file
:Gmove             git mv && rename buffer
:Gcommit           git commit
:Gread             git co -- filename on buffer (?)
:Gremove           git rm && delete buffer
:Gblame            git blame
:Gedit             view blob/tree/commit/tag
  :Gvsplit           " in vsplit
  :Gtabedit          " in new tab


RAILS
:Rserver                         Rails server
:Rake db:migrate                 run migrations
:Rake db:rollback                rollback migration
:[n,n]Rextract <partial_name>    extract lines into partial
<%= console %>                   open console inside Rails view

PRY-RAILS
rails c
show-routes --grep new
show-models
DISABLE_PRY_RAILS=1 rails console
method(:method_name).source_location
                    .owner (with gem "method_source")
                    .source
                    .comment

SNIPMATE
each followed by <tab>:
  if               if / end
  ife              if / else / end
  map              .map { || }
  ea               .each { || }
  eawi             .each_with_index { || }
  col
  sel
  cla

VIM-RUBY
(v)im              (visual select) inside method
(v)am              (visual select) around method
(v)iM              (visual select) inside class
(v)aM              (visual select) around class

SPRING
spring stop
export DISABLE_SPRING=1

GIT DIFF
:Gdiff
:diffget / do
:diffput / dp
:diffupdate

GIT
git branch --merged master  list branches merged into master
git branch --no-merged      list unmerged branches
git blame SHA^ <filename>   view earlier version of file

ITERM2
echo -e "\033];title here\007"  add title to window

OTHER
notes              open Teladoc notes

TMUX

tmux list-keys | less
tmux list-commands | less
man tmux
