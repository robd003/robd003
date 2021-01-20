```python
class RobertPalmer:

	def __init__(self):
		self.work = AllFactors("CTO")
		self.home = UnitedStates("Los Altos, CA")

	async def run(self, inputs: Union[Beer, Kvass, Plombir]) -> None:
		while True:
			await self.work.do(inputs)
		
	def sleep(self):
		raise NotImplementedError
```
