Facebook-JS-Helper
====================

Simple API of the Facebook API \o/

API
--------

	var sucess 			= function(response){}
		, error 		= function(response){}
		, permissions	= 'user_email, user_photos';

	API_FB.login(success, error, permissions);

	API_FB.getAllFriends(success, extra_fields)
	API_FB.publishProfilePhoto(photo_url, photo_msg, album_name, success, error)
	API_FB.publishCoverPhoto(photo_url, photo_msg, album_name, success, error)
	API_FB.publishPhoto(album_id, photo_url, photo_msg, success, error)
	API_FB.getAlbumId(user, name, success)
	API_FB.getListAlbums(user, success)
	API_FB.getAllAlbums(user, success)
	API_FB.createAlbum(name, description, success, error)
	API_FB.executePagging(query, finish, idQueue)