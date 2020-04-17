# Modify_Name_Shell_Programming

$name is script name

# usage:
    $name [-r] [-l|-u] <file/directory names>
    $name [-r] <sed pattern> <file/directory names>
    $name [-h]
# $name correct syntax examples:
    $name -l LEVEL1_DIR/ LEVEL1_FILE.py
    $name -u level1_dir/ level1_file.py
    $name -r -u level1_dir/
    $name sed 's/level/changed_level/' level1_dir/ level1_file.py
    $name -r sed s/level/changed_level/ level1_dir/
# $name incorrect syntax example:
    $name -r -u level1_file.py
    $name level1_file.py
   $name sed this_is_wrong_pattern level1_file.py
