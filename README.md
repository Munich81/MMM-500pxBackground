# MMM-500pxBackground

500px Api:

siehe https://github.com/500px/legacy-api-documentation

https://api.500px.com/v1/photos?feature=fresh_today&sort=created_at&image_size=3&include_store=store_download&include_states=voted&consumer_key=

only — String name of the category to return photos from. Note: Case sensitive, separate multiple values with a comma.
exclude — String name of the category to exclude photos by. Note: Case sensitive, separate multiple values with a comma.
rpp — The number of results to return. Can not be over 100, default 20.
image_size — The photo size(s) to be returned. See the documentation on photo sizes.
personalized_categories - If set to true, returns photos from personalized categories for the currently logged in user and authenticated request, if personalization is available for the current user.

https://api.500px.com/v1/photos?feature=highest_rated&image_size=4096&rpp=10&personalized_categories=true&consumer_key=
