-- Table: public.incidents

-- DROP TABLE public.incidents;

CREATE TABLE public.incidents
(
    incident_id integer NOT NULL,
    date text COLLATE pg_catalog."default",
    state text COLLATE pg_catalog."default",
    city_or_county text COLLATE pg_catalog."default",
    address text COLLATE pg_catalog."default",
    n_killed integer,
    n_injured integer,
    incident_url text COLLATE pg_catalog."default",
    source_url text COLLATE pg_catalog."default",
    incident_url_fields_missing text COLLATE pg_catalog."default",
    congressional_district integer,
    gun_stolen text COLLATE pg_catalog."default",
    gun_type text COLLATE pg_catalog."default",
    incident_characteristics text COLLATE pg_catalog."default",
    latitude double precision,
    location_description text COLLATE pg_catalog."default",
    longitude double precision,
    n_guns_involved text COLLATE pg_catalog."default",
    notes text COLLATE pg_catalog."default",
    participant_age text COLLATE pg_catalog."default",
    participant_age_group text COLLATE pg_catalog."default",
    participant_gender text COLLATE pg_catalog."default",
    participant_name text COLLATE pg_catalog."default",
    participant_relationship text COLLATE pg_catalog."default",
    participant_status text COLLATE pg_catalog."default",
    participant_type text COLLATE pg_catalog."default",
    sources text COLLATE pg_catalog."default",
    state_house_district text COLLATE pg_catalog."default",
    state_senate_district text COLLATE pg_catalog."default",
    CONSTRAINT incidents_pkey PRIMARY KEY (incident_id)
)

TABLESPACE pg_default;

ALTER TABLE public.incidents
    OWNER to postgres;