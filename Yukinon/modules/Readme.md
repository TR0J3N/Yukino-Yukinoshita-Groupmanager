## Yukinonthecutebot Example plugin format
```python3
from Yukinon.decorator import register
from .utils.disable import disableable_dec
from .utils.message import get_args_str

@register(cmds="Yukinon")
@disableable_dec("Yukinon")
async def _(message):
    j = "Hello there my name is Yukinon"
    await message.reply(j)
    

__help__ = """
<b>Hi</b>
- /hi: Hello there my name is Yukinon
"""
__mod_name__ = "Yukinon"
```
