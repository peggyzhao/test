test

<?php

class TestClass {

    function get_test($args) {
        $data = array();
        if (empty($args)) {
            return $data;
        }
        
        foreach($args as $value) {
            ...
            $data[] = $value;
        }
        
        return $data;
    }
}

?>

====

just for test by oneself
