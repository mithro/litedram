COREDIR = ../
PYTHON = python3

CMD = PYTHONPATH=$(COREDIR) $(PYTHON)

bist_tb:
	$(CMD) bist_tb.py

bist_async_tb:
	$(CMD) bist_async_tb.py

downconverter_tb:
	$(CMD) downconverter_tb.py

upconverter_tb:
	$(CMD) upconverter_tb.py

all: bist_tb bist_async_tb downconverter_tb upconverter_tb
