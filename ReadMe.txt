Find this part in Ross's doc:


Firstly, you will need to add new member variables m_enableRotation, m_previousPosition and m_previousSpeed. 
Rotations should be enabled initially, but are disabled when there is a collision. Rotations should be re-enabled after a collision has been 
resolved (think about where this should happen). The variable m_previousPosition should always be updated before the tank moves to a new position. 
We will deal with m_previousSpeed shortly.