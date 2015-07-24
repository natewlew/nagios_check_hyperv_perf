# Nagios Check Hyperv Performance Plugin

Plugin to Show Hyper-V Performance

See: https://exchange.nagios.org/directory/Plugins/Operating-Systems/*-Virtual-Environments/Others/Check-Hyperv-Performance/details

# Install:

* Copy this file to your plugins directory
* Modify `$check_nt_path` and use lib if necessary
* Copy `check_hyperv_perf.php` to your pnp4nagios template directory (optional).
  This makes your graphs look better.
* Use the `check_hyperv_perf_example.cfg` as a starting point for your
  nagios config. Take note that you need a host variable called `_vm_list`.
  This is a comma seperated list of you guest vm names. I am pretty sure
  this is case sensitive.
