**Task #1:** Find the api call that allows you to search for all images of "cats".

API Call: https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=739b0fab4b412a82fd7994063237ef68&tags=cat&format=json


**Task #2:** Find the api call that allows you to search for all images from "Charlotte, North Carolina.

Method 1 - use lat/long for Charlotte:

API Call: https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=739b0fab4b412a82fd7994063237ef68&lat=35.227087&lon=-80.843127&radius=10&radius_units=km&format=json

Method 2 - user flicker place finder:

API Call 1: https://api.flickr.com/services/rest/?method=flickr.places.find&api_key=739b0fab4b412a82fd7994063237ef68&query=Charlotte%2C+North+Carolina&format=json
API Call 2: https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=739b0fab4b412a82fd7994063237ef68&place_id=KtHrHAVTUb1F.npO&format=json

**Task #3:** Get all of the comments for any photo.

API Call: https://api.flickr.com/services/rest/?method=flickr.photos.comments.getList&api_key=739b0fab4b412a82fd7994063237ef68&photo_id=18149663983&format=json


**Task #4:** Search for a list of all the photos in your current latitude and longitude.

API Call: https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=739b0fab4b412a82fd7994063237ef68&lat=40.739885&lon=-73.990082&radius=0.5&radius_units=km&format=json
