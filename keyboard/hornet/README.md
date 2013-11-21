Hornet keyboard firmware
========================
DIY compact split keyboard designed by Phil Pirozhkov (philpirj).

## Threads
- [Prototyping](http://deskthority.net/workshop-f7/codename-hornet-t4488.html)


## Build
Move to this directory then just run `make` like:

   $ make -f Makfile.[pjrc|lufa]

Use `Makefile.pjrc` if you want to use PJRC stack or use `Makefile.lufa` for LUFA stack.


## Boot Magic
Plugin pressing these `Boot Magic` key.

- `Fn` key for bootloader kick up.
- `D` key for Debug enable.


## Keymap

### Modifiers row (common)

Tap:    

    Spc Spc Esc Tab Del   Tab AGr Bsp Ent Ent

Hold:   

    Lr1 Sft Ctl Alt Met   Met AGr Ctl Sft Lr1

### Default layer
    ` q w e r t    y u i o p =
    \ a s d f g    h j k l ; '
    [ z x c v b    n m , . / ]

### Shifted layer (Shift hold)

    ~ Q W E R T    Y U I O P +
    | A S D F G    H J K L : "
    { Z X C V B    N M < > ? }

### Special layer: (Lr1 hold)
      1 2 3 4 5    6 7 8 9 0 -
      ↰ ↑ ↳ ⤒    ← ↓ ↑ →  
      ← ↓ → ⤓    
