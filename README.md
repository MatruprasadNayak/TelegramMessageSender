## • How To Install and Use

`$ git clone https://github.com/erfan4lx/TelegramBulkMessageSender.git`

`$ cd TelegramBulkMessageSender`

* Install requierments

`$ python3 setup.py -i`

* setup configration file ( apiID, apiHASH )

`$ python3 setup.py -c`

* To Scrape Users from group

`$ python3 scraper.py`

* ( members.csv is default if you changed name use it )
* Send Bulk sms To Collected Data 

`$ python3 smsbot.py members.csv`
