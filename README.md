# NicolasBlackburnThesis


Login To 
hostname:  129.94.175.194
userId: nicolas
password: nicolas1
ssh into cse via sshcse
ssh into  129.94.175.194 via ssh  129.94.175.194 -p 5432

postgres via pgAdmin
- turn on tunnelblick
- dbname socdbs
- fill in username + pw same as linux machine

next steps
- merge data + upload csv into db

CREATE TABLE tmk_annual_release (
  primary_key VARCHAR(10),
  ccode VARCHAR(10),
  year VARCHAR(10),
  tmk_ongoing VARCHAR(10),
  genpol_ongoing VARCHAR(10),
  tmk_onset VARCHAR(10),
  tmk_onse_sum VARCHAR(10),
  PRIMARY KEY (primary_key)
);