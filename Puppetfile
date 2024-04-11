forge "https://forgeapi.puppetlabs.com"

mod 'puppetlabs-firewall', '2.8.1'

#specify powershell version to avoid dependency conflict
mod 'puppetlabs-docker', '3.14.0'
mod 'puppetlabs-powershell', '2.3.0'
mod 'puppetlabs-stdlib', '4.25.1'

mod 'puppetlabs-apache', '5.10.0'
mod 'puppetlabs-concat', '6.4.0'
mod 'puppetlabs-ntp', '8.5.0'
mod 'puppetlabs-vcsrepo', '3.2.1'
mod 'voxpupuli-jenkins', 
  :git => 'https://github.com/Sakura286/puppet-jenkins',
  :ref => 'master'
mod 'puppet-python', '5.0.0'
mod 'claranet-newrelic', '2.4.2'

mod 'saz-timezone', '6.1.0'

# avoid error
# Puppet (err): Evaluation Error: Resource type not found: Deferred
# (file: /root/buildfarm_deployment/modules/systemd/manifests/unit_file.pp, line: 71, column: 47) on node
mod 'puppetlabs-systemd' '3.2.0'
