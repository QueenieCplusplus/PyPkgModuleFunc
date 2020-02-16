# PyPkgModuleFunc
to have a landscape view in PKG and Module strucure

practice <https://pyliaorachel.github.io/blog/tech/python/2017/09/15/pythons-import-trap.html>

# to declare a folder as PKG, to declare a file as a module

using 

     __init__.py (empty file)

# to know the Project Structure

    $cd <pkg>
    $ls
    
    __init__.py           qsModule.py           qsModule.pyc          to_import_a_module.py
    
    
    QsPKG(as a root folder or PKG) ---- __init__.py
                                   ---- qsModuel.py (inclue a method)
                                   ---- to_import_a_module.py(to import other method from subling module)

# to have the import (explicit or relative)

# to do Unit Test in Terminal

    $cd <root folder> #or <pkg name>
    $cd QsPKG
    
    #ls #see structure
    
    $python3 -m < module_name > . <extention name>
    $python3 -m qsMoule.py
