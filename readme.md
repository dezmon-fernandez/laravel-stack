## Laravel PHP Framework 

Last updated on Tuesday, October 21st, 2014.

This repository is simply the Laravel framework with all the vendor files provided and the debug configuration set to true. This way, someone who is unfamiliar with Composer can skip that step in the setup process all together.

To use, fork this repository (or download the ZIP and extract) into the root of your LAMP stack. Afterwards, give the server access to the `app/storage` folder. Once in the directory of the Laravel stack, the command for this for Unix machines is `chmod -R o+w app/storage`.

Given that your LAMP stack is properly configured, this should set you on your way to developing with Laravel. Check by  browsing to the `public` directory off of your LAMP stack.

If not, check the PHP configuration of your environment using `phpinfo()` and verify that `mcyrpt` is enabled along with `mod_rewrite`. Any further help should be requested on Piazza.

This repository is made for CSCI445, Fall of 2014 at the Colorado School of Mines. This is not intended for production environments and should only be used for educational purposes.
