## Queue Settings, Queue Names must not have whitespace, or HTML ids fail! */


` $conf['queue']['budget']['cpu']            = 8;`

` $conf['queue']['budget']['memory']         = 24;`

` $conf['queue']['budget']['nodes']          = 10;`


## Recommended and Optional Settings we want the user to specify 

`$conf['settings']['recommended']            = array('M','N','d');`

`$conf['settings']['optional']               = array('e','A');`


## Torque Qsub Settings */

`$conf['param']['a']['description']          = 'Date / Time';`

`$conf['param']['a']['example']              = '02/02/1989';`


## Parameters that require two switches , aka email
should have the parameter as its value, and you must handle the logic in the javascript function 

`$conf['param']['m']['description']          = '';`

`$conf['param']['m']['example']              = '';`

`$conf['param']['m']['special_case']         = 'm';`

