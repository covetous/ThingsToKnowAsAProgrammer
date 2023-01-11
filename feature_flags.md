# Feature flags 
Feature flags is a way of managing if a feature should be available to a specific user or group of users. 

Example of how to handle feature flags in your organization.
>Use the following a naming convention section_featurepurpose_layer
>
>As a team limit the number of active flags you allow your team to use. This will encourage cleanup of released feature flags.
>
>Limit a feature flag to one team. Don't allow the same flag to be used by multiple teams to keep ownership of the flag clear.
>
>Keep feature flag implementation simple.
>
>Put the flag at the highest common access point.
>Avoid nesting multiple flags as this make enabling and removing feature flags difficult.
