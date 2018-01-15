# edit
Version 0.2.0

Add-on for todo.sh to open todo.txt in vi

## Installing

```
cd ~/.todo.actions.d
git clone git@github.com:betsythefc/edit.git
```

set the EDITOR variable to use a different editor than vi.

```
echo "export EDITOR='/path/to/editor'" >> ~/.bash_profile
source ~/.bash_profile
```

## Usage

```
$ todo.sh list
(A) 2018-01-04 Clean @Apartment due:2018-01-08
(B) 2018-01-04 Finish homework
$ todo.sh edit
```
