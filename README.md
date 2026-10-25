# d4vut
Dragonbound Wings of Magic Offset Dump  25.10.2026

MoveModule.set_moveSpeed | 0x3A8120 | Movement speed setter 
MoveModule.set_tmpMovingSpeedScale | 0x3A8130 | Movement speed scale (0xB4) 
MoveModule.set_curRealPos | 0x3A8080 | Current real position 
MoveModule.set_curRealSpeed | 0x3A80A0 | Current real speed 
MoveJumpModule.OnJumpStart | 0x3A1060 | Jump start handler 
MoveJumpModule.JumpUp | 0x3A0420 | Jump trigger 
PropertyModule.set_curActualHp | 0x3287E0 | Set current HP
PropertyModule.set_maxHp | 0x3ADE60 | Set maximum HP 
UseSkillModule.StartCastSkill | 0x3BA7C0 | Skill cast entry point 
UserTargetMgr.SetSkillAutoTargetId | 0x47E770 | Skill auto-target ID setter 
EntityManager.get_userEntityID | 0x36F110 | Get local player entity ID 
EntityManager.set_userEntityID | 0x36FCE0 | Set local player entity ID 

TypeInfo (static)
EntityManager_TypeInfo 0x245D6F8 · UserTargetMgr_TypeInfo 0x244E990 · MoveModule_TypeInfo 0x2487400 · MoveJumpModule_TypeInfo 0x2487350 · PropertyModule_TypeInfo 0x2425E70

Field offsets (Class	Fields)
MoveModule	mMoveJumpModule 0x58 · curClientWantPos 0x60 · moveSpeed 0x78 · curRealPos 0x7C · curRealSpeed 0x94 · tmpMovingSpeedScale 0xB4
MoveJumpModule	mJumpInitialVelocity 0x20 · s_Jump_Height 0x1C · s_JumpSpeedRate 0x48
PropertyModule	m_CurActualHp 0x20 · m_CurrentHp 0x38 · m_MaxHp 0x48
BaseEntity	m_EntityID 0x10 · m_RelationType 0x44 · m_IsAlwaysVisibility 0x4C · m_Pos 0xA4
UserEntity	userEntityID 0x38 · m_ReportMoveSpeed 0x458 · m_ForceMoveReport 0x4A9
UserTargetMgr	mTargetId 0x30 · m_LookTargetId 0x40
