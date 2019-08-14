# libft

The aim of this project is to code a C library regrouping usual functions: math, text, strings, memory, data structures etc.

## **Functions**

For the sake of keeping everything neat and in order, I separated the functions' declarations into different header files, corresponding to the behavior of such functions. For instance, ft_strlen can be found in ft_string.h. Also, some of the functions included don't exist in the Standard C Library, but I still kept them defined by there behavior. For example, ft_strnew can also be in ft_string.h.

[Untitled](https://www.notion.so/4573ebe5d4234d7ca87c8db93d6e59e9)

## **Setup**

Download the repository, and compile the library using the Makefile. You can use the following commands:

[Untitled](https://www.notion.so/49bff0e384254387b09e3dfd56c24c8a)

The binary `libft.a` will be created at the root of the project's directory.

## **Install**

### **Local**

Copy the `includes/` directory into the root of your project, and make sure to compile your source code with the following flags:

    gcc libft.a -I./includes <your_file.c> -o <output_name>

### **Global**

Run the following command :

    make install

Now you can add the `<libft.h>` header in your .c files!
