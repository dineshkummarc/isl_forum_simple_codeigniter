Notes for insilico peoples.
--------------------------------------------------------------------------------
to get set up
go to config.php and modify base url to whatever you need the root directory to be

$config['base_url']	= 'http://localhost/isl_forum_simple_codeigniter/';

--------------------------------------------------------------------------------

then import the sql file from the root directory, into a local lamp install and call the db whateve you want on import

--------------------------------------

lastly go to database.php and change the following stuff to be relevent to your db

$db['default']['hostname'] = 'localhost';
$db['default']['username'] = 'root';
$db['default']['password'] = 'pass';
$db['default']['database'] = 'forum_db';
$db['default']['dbdriver'] = 'mysql';
$db['default']['dbprefix'] = '';
$db['default']['pconnect'] = TRUE;
$db['default']['db_debug'] = TRUE;
$db['default']['cache_on'] = FALSE;
$db['default']['cachedir'] = '';
$db['default']['char_set'] = 'utf8';
$db['default']['dbcollat'] = 'utf8_general_ci';
$db['default']['swap_pre'] = '';
$db['default']['autoinit'] = TRUE;
$db['default']['stricton'] = FALSE;

==================================================================================
by default the passwords are hashed, so do log in as a high level admin use

username: admin
password: 123123