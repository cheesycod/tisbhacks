# site

Site source code

### Usage

Get Youtube Data API keys from https://developers.google.com/youtube/v3

1. Either restore from backup or load ``sdk/schema.sql`` to a PostreSQL 14 database named ``kalam`` (``\c kalam`` and then ``\i sdk/schema.sql``)
2. Install ``cython``, then do ``pip3 install -r requirements.txt``
3. Bulld shiksdk from sdk/shiksdk
4. Run sdk/shiksdk/shiksdk devserver to run the devserver. Go to http://127.0.0.1:8000/data/build

Developed by: [cheesycod](https://github.com/cheesycod) AKA Sanandan Sashikumar
