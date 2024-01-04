pip install google-api-python-client
!pip install pymongo
import pandas as pd
from googleapiclient.discovery import build
from pprint import pprint
from googleapiclient.errors import HttpError
import pymongo 
api = 'AIzaSyDMgdCRGCieAGvUdh8wcH3CPDLmOg_y44I'
api_service_name = "youtube"
api_version = "v3"
youtube =build(api_service_name, api_version, developerKey=api)
