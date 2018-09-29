# How to write code productively

1. Always using descriptive name
    ```python
      # This is not good
      def a():
        return "a"
    ```
1. Always write good document
    ```python
    def add(a, b):
    """
    Add two numbers together

    :return: sum of two number
    :raise: TypeError when arguments are not number
    """
    if type(a) != int or type(b) != int:
      raise TypeError
    return a + b
    ```
1. Implement unittest
1. Use Agile Development Process