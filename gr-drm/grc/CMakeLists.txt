# Copyright 2011 Free Software Foundation, Inc.
#
# This file is part of GNU Radio
#
# GNU Radio is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3, or (at your option)
# any later version.
#
# GNU Radio is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with GNU Radio; see the file COPYING.  If not, write to
# the Free Software Foundation, Inc., 51 Franklin Street,
# Boston, MA 02110-1301, USA.
install(FILES
    drm_scrambler_bb.xml
    drm_audio_encoder_sb.xml
    drm_generate_fac_b.xml
    drm_generate_sdc_b.xml
    drm_add_tailbits_bb.xml
    drm_punct_bb.xml
    drm_interleaver_bb.xml
    drm_interleaver_cc.xml
    drm_partitioning_4_bb.xml
    drm_partitioning_16_bb.xml
    drm_partitioning_64sm_bb.xml
    drm_cell_mapping_cc.xml
    drm_qam_map_bc.xml
    drm_m3ufile_source_f.xml DESTINATION share/gnuradio/grc/blocks
)
