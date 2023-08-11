# Government-Military-Database-System

Data Collection and Entity Sets Identification
Entity sets:
Soldier:

Attributes: s_id (PK), s_firstn, s_lastn, s_DOB, s_age, s_gen, s_rank, s_posting, s_cor, s_state, s_phone (multivalued), s_email, ismarried.
Father:

Attributes: f_id (PK), f_firstn, f_lastn, f_DOB, f_phone (multivalued), f_email, f_age (derived), f_city, f_state, f_adline.
Mother:

Attributes: m_id (PK), m_firstn, m_lastn, m_DOB, m_phone (multivalued), m_email, m_age (derived), m_city, m_state, m_adline.
Spouse:

Attributes: sp_id (PK), sp_firstn, sp_lastn, sp_DOB, sp_phone (multivalued), sp_email, sp_age (derived), sp_gen, sp_city, sp_state, sp_adline.
Medical:

Attributes: m_id (PK), bg, height, weight, hearing, isdiabetic.
Vaccine:

Attributes: v_id (PK), polio, tetanus, DDT, HIV, POX.
Skillset:

Attributes: sk_id (PK), sprint_speed, climb_speed, computing, teamwork.
Arms_used:

Attributes: a_id (PK), INAS, AK103, MG56, AKM, Dragunov_svd59.
Bank:

Attributes: ifsc (PK), b_name, b_branch.
