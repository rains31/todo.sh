[中文版帮助](./README_zh.md)

This is a Todo tool implemented in Shell, and below is its usage instructions:

## Usage

```
todo [options] [arguments]
```

## Options

- `-a` or `--add`: Add a task to the todo list.
- `-d` or `--done`: Mark a task as completed.
- `-u` or `--undo`: Undo a completed task.
- `-D` or `--del` or `--delete`: Delete a task.
- `-r` or `--recycle`: Clear completed tasks.
- `-s` or `--sort`: Sort tasks by task number.
- `-l` or `--list` or empty option: Display the task list.
- `-h` or `--help`: Display help information.

## Arguments

- `add`: The content of the task to be added.
- `done`: The task number to mark as completed.
- `undo`: The task number to undo completion.
- `delete`: The task number to delete.
- `lineNum`: Starting line number for operations.
- `toLineNum`: Ending line number for operations.

## Examples

- Add a task:
```
todo -a "Buy groceries"
```

- Mark a task as completed:
```
todo -d 1
```

- Undo a completed task:
```
todo -u 1
```

- Delete a task:
```
todo -D 1
```

- Clear completed tasks:
```
todo -r
```

- Sort the task list:
```
todo -s
```

- Display the task list:
```
todo -l
```

- Display help information:
```
todo -h
```

Note: If no option is provided, the arguments will be treated as the content of a task to be added to the list.

```
# The following two commands have the same effect
todo Buy groceries 
todo -a Buy groceries
```

You can choose appropriate options and arguments to manage your task list according to your needs.