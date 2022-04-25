# JMeter Upgrade Strategy

## Strategy

- [ ] Why you should upgrade?
  - [ ] Performance improvements
  - [ ] New features
  - [ ] Security fixes
  
- [ ] Why leaders are so reluctant?
  - [ ] Legacy apps/scripts
  - [ ] Breaking changes
  - [ ] Apathetic

- [ ] Backup 
  - [ ] Test Plans
  - [ ] Test Data
  - [ ] JARs
  - [ ] List of Plugins used and its version
  - [ ] Properties
  - [ ] Certificates and credentials

- [ ] Release Notes
  - [ ] Read and understand the major/minor new features and enhancements
  - [ ] Understand the bugfixes and known issues
  - [ ] Understand the breaking features if any
   
- [ ] Upgrade
  - [ ] Download and extract the newer version of JMeter   
  - [ ] Launch JMeter and open the test plan
  - [ ] Smoke Test

- [ ] Not able to open
  - [ ] Plugins
  - [ ] JARs
  - [ ] Check the log file to troubleshoot

- [ ] Not working as intended
  - [ ] JARs
  - [ ] Properties
  - [ ] Certificates and credentials
  - [ ] Check if any breaking changes
  - [ ] Check the log file to troubleshoot

- [ ] Strategy
  - [ ] Work as a team
  - [ ] Automate e.g bash to terraform
  - [ ] Baseline the performance 
  - [ ] Deploy a upgrade plan
    - [ ] Every major release
    - [ ] Only critical fixes
    - [ ] Every quarter/half-yearly/annual
