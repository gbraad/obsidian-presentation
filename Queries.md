# Queries

## Basic list

```dataview
LIST

```

Note: the empty line is important


## Where clause

```dataview
LIST
WHERE type="investment"
```

## And parameter

```dataview
LIST
WHERE type="investment"
  AND sold="no"
```

## Table with parameters

```dataview
TABLE description as Description, sold as Sold
WHERE type="investment"
```

## Basic task list

```dataview
task

```

## Task list in short format

```tasks
short mode
```

## Only show not done tasks

```tasks
not done
short mode
```
