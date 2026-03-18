# What engineers should do if deployment fails

## 1. Trigger an immediate rollback

- The first priority is restoring service to users. Revert the production environment to the last known stable version

## 2. Isolate and Stabilize the environment

- Once the rollback is sucessful, ensure the system is stable

## 3. Review logs and observability data

- Examine logs, error trackers and deployment events to identify exactly where the break ocurred

## 4. Reproduce the Failure in Staging

- Before attempting a fix, move the investigation back to a non-production environment. Attempt to replicate the crash or error in a Staging or Pre-production environment that mirrors the production setup.

## 5. Conduct a Blameless Post-Mortem

- Once the issue is resolved and the fix is deployed, the team should meet to document the incident.


