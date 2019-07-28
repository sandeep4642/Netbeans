SET SCHEMA consult;

ALTER TABLE consultant DROP CONSTRAINT consult_consultant_fk_status_id;
ALTER TABLE consultant DROP CONSTRAINT consult_consultant_fk_recruiter_id;

ALTER TABLE client DROP CONSTRAINT consult_client_fk_billing_address;
ALTER TABLE client DROP CONSTRAINT consult_client_uq_billing_address;

ALTER TABLE recruiter DROP CONSTRAINT consult_recruiter_fk_client_name;

ALTER TABLE project DROP CONSTRAINT consult_project_fk_client_name;

ALTER TABLE project_consultant DROP CONSTRAINT consult_project_consultant_fk_project_name;
ALTER TABLE project_consultant DROP CONSTRAINT consult_project_consultant_fk_consultant_id;

ALTER TABLE billable DROP CONSTRAINT consult_billable_fk_consultant_id;
ALTER TABLE billable DROP CONSTRAINT consult_billable_fk_project_name;

DROP TABLE address;
DROP TABLE consultant_status;
DROP TABLE consultant;
DROP TABLE client;
DROP TABLE recruiter;
DROP TABLE project;
DROP TABLE project_consultant;
DROP TABLE billable;

DROP SCHEMA consult RESTRICT;