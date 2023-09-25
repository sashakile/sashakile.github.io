To install dependencies

   python -m venv venv
   source ./venv/bin/activate.fish #on fish
   python -m pip install -r requirements.txt

Configuration file for the site is ``conf.py``.

To build the site::

    nikola build

To see it::

    nikola serve -b

To create new post::

   nikola new_post -f markdown

To publish to GH Pages::

   nikola github_deploy

To check all available commands::

    nikola help
