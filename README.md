# Government-Military-Database-System

Data Collection and Entity Sets Identification
Entity sets:
Soldier(s_id, s_firstn, s_lastn, s_DOB, s_age, s_gen, s_rank, s_posting, s_cor, s_state, 
s_phone,s_email, ismarried)

This entity set is used to store details about the soldier. s_id is the primary key.
In this entity set : The attribute s_phone is multivalued. The attribute s_age is derived from 
s_DOB.The rest of the attributes are all simple and single valued
Father(f-id, f_firstn, f_lastn, f_DOB, f_phone, f_email , f_age, f_city, f_state, f_adline)

This is to record information related to the soldier’s father. f_id is the primary key for this table. 
In this entity set: The attribute f_phone is multivalued. The attribute f_age is derived from f_DOB. 
The rest of the attributes are all simple and single valued.

Mother(m-id, m_firstn, m_lastn, m_DOB, m_phone, m_email , m_age, m_city, m_state, 
m_adline)
This is to record information related to the soldier’s mother. m_id is the primary key for this table. 
In this entity set: The attribute m_phone is multivalued. The attribute m_age is derived from 
m_DOB. The rest of the attributes are all simple and single valued.

Spouse(sp_id, sp_firstn, sp_lastn, sp_DOB, sp_phone, sp_email , sp_age, sp_gen, sp_city, 
sp_state, sp_adline)
This is to record information related to the soldier’s spouse. sp_id is the primary key for this table. 
In this entity set: The attribute sp_phone is multivalued. The attribute sp_age is derived from 
sp_DOB. The rest of the attributes are all simple and single valued.

Medical(m_id, bg, height, weight, hearing, isdiabetic)
This table is to record the soldier’s basic medical data.m_id is the primary key for this table.
In this entity set all the attributes are simple and single valued.

Vaccine(v_id, polio, tetanus, DDT, HIV, POX)
The list of vaccines that the soldier has taken is stored in this table. The primary key is v_id.
In this entity set all the attributes are simple and single valued.
Skillset(sk_id, sprint_speed, climb_speed, computing, teamwork) 
This table stores the skillsets of the soldier. The primary key is sk_id. 
In this entity set all the attributes are simple and single valued.

Arms_used(a_id, INAS, AK103, MG56, AKM, Dragunov_svd59) Arms used by the soldier are 
stored in this table. a_id is the primary key. In this entity set all the attributes are simple and 
single valued.

Bank(ifsc, b_name, b_branch)
This table stores the bank details of the soldier. ifsc is the primary key. 
In this entity set all the attributes are simple and single valued.
