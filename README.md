'''''''''''''
cd info_segugio
poetry install 
eval $(poetry env activate)
poetry run chainlit run src/info_segugio/__init__.py -w
tavily