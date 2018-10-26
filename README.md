# Instamojo Payment api for codeigniter
Instamojo Payment api written for Codeigniter ( Tested with 2.x )

# Database support 

1. Activate database support by setting `$config['mojo_db']  = true ;` on `config/instamojo.php`

2. Set table name on `$config['mojo_table']  = 'table_name' ;` 

3. That's it !

Read more on `config/instamojo.php`

# Installation 

Copy the three folders into application directory

Edit config/instamojo.php with your credentials

# Example Usage

    Initializing instamojo library
    $this->load->library('instamojo');

    Fetching all the payment request details.
		$result = $this->instamojo->all_payment_request();
		print_r($result);
    

    NB: Please go through controller/example.php to try basic checkout
 
