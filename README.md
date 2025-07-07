# z_if_else_example.abap
REPORT z_if_else_example.

DATA: lv_value TYPE i VALUE 15.

IF lv_value > 10.
  WRITE: / 'Value is greater than 10'.
ELSE.
  WRITE: / 'Value is 10 or less'.
ENDIF.
