To compile

- First make edits to respective jemdoc file in ``jemdoc_files/``. For example, index.jemdoc
- Once the changes are made, execute the command (if it's index file the command will have that jemdoc file) ``python jemdoc.py -c mysite.conf index.jemdoc``
- The above command creates ``index.html``. Move this file to ``docs/`` folder. 
- Commit and push the code for the changes.