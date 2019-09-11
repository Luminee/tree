# Tree
Build Tree And [getChildren, getParents]

## Installation

Install through Composer.

```
composer require luminee/tree
```

Or download the file in `src/Tree.php`

## Usage

```
$Tree = new Tree();
$Tree->buildTree($array);

$item = $Tree->getTree(); // Get Tree
$item = $Tree->getChildren('group1', 'group') // Find Item and Its Children
$item = $Tree->getParents('group1', 'group') // Find Item and Its Parents

$option = ['parent' => 'pre', 'children' => 'childs', 'parent_id' => 'pid']
// Customize tree keys
$Tree = new Tree($option);

```
