# Vimwiki -> Vim

## Normal mode
		r<any char>		(Replace current char with given char)
		yy						(To yank a line)
		<num>yy     	(To yank <num> lines)
		o							(Add line below)
		O							(Add line above)
		A							(Go into insert mode at end of line)		
		v + </>				(Shift selected line(s))
	
	
		### Word
		vep						(Replace word with what was previously yanked)
		daw						(Delete previous word)
		b							(Go back a word)
		e							(Go forward a word)
		"+y						(yank to system clipboard)
		
		### [Fold](Fold)		
		### [Marks](Marks)
		### [Selection](Selection)	
		### [Scrolling](Scrolling)
		### [Cursor](Cursor)
		

## Command mode
		:set scrolloff=<any num> (Keep (num) lines above and below the cursor)
		:set nonumber (Remove line number count)
		:set number 	(Add line number count)
		:set noh			(Remove highlighting)
		:%y+					(Yank to system clipboard)
		:marks				(View all created marks)
	
## Visual block mode (ctrl-v)
		<select-text><shift-i>	(insert text for all lines selected)
