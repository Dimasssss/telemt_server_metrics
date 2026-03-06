# Server Metrics 2026-03-06 16:26:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 21881.4 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656730
telemt_connections_bad_total 9747
telemt_handshake_timeouts_total 3068
telemt_upstream_connect_attempt_total 10661
telemt_upstream_connect_success_total 10594
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 10622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 2015
telemt_me_reconnect_success_total 2000
telemt_me_reader_eof_total 2100
telemt_me_idle_close_by_peer_total 2100
telemt_me_route_drop_no_conn_total 279435
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3398
telemt_desync_full_logged_total 812
telemt_desync_suppressed_total 2586
telemt_desync_frames_bucket_total{bucket="1_2"} 816
telemt_desync_frames_bucket_total{bucket="3_10"} 1167
telemt_desync_frames_bucket_total{bucket="gt_10"} 1415
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2102
telemt_me_writer_restored_same_endpoint_total 1994
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 565310
telemt_user_connections_current{user="hello"} 1071
telemt_user_octets_from_client{user="hello"} 12764379000 (11.89 GB)
telemt_user_octets_to_client{user="hello"} 211076375456 (196.58 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 21881.3 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248377
telemt_connections_bad_total 867
telemt_handshake_timeouts_total 7134
telemt_upstream_connect_attempt_total 10400
telemt_upstream_connect_success_total 10375
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 10400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 953
telemt_me_reconnect_success_total 935
telemt_me_reader_eof_total 986
telemt_me_idle_close_by_peer_total 986
telemt_me_route_drop_no_conn_total 141882
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 823
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 557
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 6
telemt_pool_force_close_total 239
telemt_me_writer_removed_unexpected_total 987
telemt_me_writer_restored_same_endpoint_total 935
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 228318
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 2624135504 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 91823842448 (85.52 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 21881.2 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493400
telemt_connections_bad_total 5420
telemt_handshake_timeouts_total 50688
telemt_upstream_connect_attempt_total 18055
telemt_upstream_connect_success_total 17974
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 18041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 6026
telemt_me_reconnect_success_total 6000
telemt_me_reader_eof_total 6342
telemt_me_idle_close_by_peer_total 6342
telemt_me_route_drop_no_conn_total 250097
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1058
telemt_desync_full_logged_total 315
telemt_desync_suppressed_total 743
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 408
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 6354
telemt_me_writer_restored_same_endpoint_total 5993
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 359
telemt_user_connections_total{user="hello"} 421959
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 6137990300 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 131762023420 (122.71 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 21197.2 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439182
telemt_connections_bad_total 138680
telemt_handshake_timeouts_total 11391
telemt_upstream_connect_attempt_total 11801
telemt_upstream_connect_success_total 11800
telemt_upstream_connect_attempts_per_request{bucket="1"} 11800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4804
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 2359
telemt_me_reconnect_success_total 2341
telemt_me_reader_eof_total 2393
telemt_me_idle_close_by_peer_total 2393
telemt_me_route_drop_no_conn_total 138895
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 348
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 2399
telemt_me_writer_restored_same_endpoint_total 2340
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 253168
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 4474392236 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 90533206216 (84.32 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 21881.3 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393405
telemt_connections_bad_total 11050
telemt_handshake_timeouts_total 3462
telemt_upstream_connect_attempt_total 9764
telemt_upstream_connect_success_total 9752
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4381
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 1766
telemt_me_reconnect_success_total 1750
telemt_me_reader_eof_total 1845
telemt_me_idle_close_by_peer_total 1844
telemt_me_route_drop_no_conn_total 193103
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 747
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 222
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1849
telemt_me_writer_restored_same_endpoint_total 1747
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 360927
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 15335356444 (14.28 GB)
telemt_user_octets_to_client{user="hello"} 184572236944 (171.90 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 86
```