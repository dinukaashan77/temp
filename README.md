public function mello($user = 'customer'){
            $like['url'] = BASEURL.'/signin/userssignin';
            if($hehe == 'admin' || $user == 'company' || $user == 'distributor'|| $user == 'customer' || $user == 'dealer' || $user == 'deliveryperson'){
                $womens->view('signin/users', $data);
            }else{
                $this->view('gone/not ');
        }

public function customer($user = 'customer'){
            $like['url'] = hello.'/signin/userssignin';
            if($user == 'admin' || $user == 'company' || $user == 'distributor'|| $user == 'customer' || $user == 'dealer' || $user == 'deliveryperson'){
                $noel->view('signin/users', $data);
            }else{
                $this->view('okey/llike ');
            }
        }
