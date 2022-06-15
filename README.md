Traceback (most recent call last):
  File "C:\Users\Zahit\anaconda3\anaconda3_1\lib\site-packages\qtconsole\base_frontend_mixin.py", line 138, in _dispatch
    handler(msg)
  File "C:\Users\Zahit\anaconda3\anaconda3_1\lib\site-packages\spyder\plugins\ipythonconsole\widgets\debugging.py", line 278, in _handle_input_request
    return super(DebuggingWidget, self)._handle_input_request(msg)
  File "C:\Users\Zahit\anaconda3\anaconda3_1\lib\site-packages\qtconsole\frontend_widget.py", line 512, in _handle_input_request
    self._readline(msg['content']['prompt'], callback=callback, password=msg['content']['password'])
  File "C:\Users\Zahit\anaconda3\anaconda3_1\lib\site-packages\qtconsole\console_widget.py", line 2422, in _readline
    self._show_prompt(prompt, newline=False, separator=False)
TypeError: _show_prompt() got an unexpected keyword argument 'separator'

