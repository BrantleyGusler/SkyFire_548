# Copyright (C) 2011-2020 Project SkyFire <http://www.projectskyfire.org/
# Copyright (C) 2008-2021 TrinityCore <http://www.trinitycore.org/>
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

set(scripts_STAT_SRCS
  ${scripts_STAT_SRCS}
  Pet/pet_dk.cpp
  Pet/pet_generic.cpp
  Pet/pet_hunter.cpp
  Pet/pet_mage.cpp
  #Pet/pet_monk.cpp
  Pet/pet_priest.cpp
  Pet/pet_shaman.cpp
  #Pet/pet_warlock.cpp
)

message("  -> Prepared: Pet")
