# Server Metrics 2026-03-06 17:59:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 27434.5 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814135
telemt_connections_bad_total 13502
telemt_handshake_timeouts_total 3503
telemt_upstream_connect_attempt_total 13687
telemt_upstream_connect_success_total 13602
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 13637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 2672
telemt_me_reconnect_success_total 2651
telemt_me_reader_eof_total 2778
telemt_me_idle_close_by_peer_total 2778
telemt_me_route_drop_no_conn_total 339279
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 4108
telemt_desync_full_logged_total 1018
telemt_desync_suppressed_total 3090
telemt_desync_frames_bucket_total{bucket="1_2"} 979
telemt_desync_frames_bucket_total{bucket="3_10"} 1459
telemt_desync_frames_bucket_total{bucket="gt_10"} 1670
telemt_pool_swap_total 5
telemt_pool_force_close_total 313
telemt_me_writer_removed_unexpected_total 2781
telemt_me_writer_restored_same_endpoint_total 2645
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 696456
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 14187595264 (13.21 GB)
telemt_user_octets_to_client{user="hello"} 257948995996 (240.23 GB)
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 27434.3 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300496
telemt_connections_bad_total 1138
telemt_handshake_timeouts_total 8610
telemt_upstream_connect_attempt_total 12371
telemt_upstream_connect_success_total 12338
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 12371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 992
telemt_me_reconnect_success_total 967
telemt_me_reader_eof_total 1023
telemt_me_idle_close_by_peer_total 1023
telemt_me_route_drop_no_conn_total 160107
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 976
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 667
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 7
telemt_pool_force_close_total 282
telemt_me_writer_removed_unexpected_total 1024
telemt_me_writer_restored_same_endpoint_total 967
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 277079
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 3406792164 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 109609918588 (102.08 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 27434.2 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 585587
telemt_connections_bad_total 5573
telemt_handshake_timeouts_total 53769
telemt_upstream_connect_attempt_total 23408
telemt_upstream_connect_success_total 23292
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 23377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 345
telemt_me_reconnect_attempts_total 7992
telemt_me_reconnect_success_total 7959
telemt_me_reader_eof_total 8458
telemt_me_idle_close_by_peer_total 8458
telemt_me_route_drop_no_conn_total 309644
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1543
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 1090
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 571
telemt_desync_frames_bucket_total{bucket="gt_10"} 623
telemt_pool_swap_total 3
telemt_pool_force_close_total 237
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 8473
telemt_me_writer_restored_same_endpoint_total 7952
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 505825
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 7408332560 (6.90 GB)
telemt_user_octets_to_client{user="hello"} 154836036544 (144.20 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 26750.3 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573229
telemt_connections_bad_total 197085
telemt_handshake_timeouts_total 15271
telemt_upstream_connect_attempt_total 18209
telemt_upstream_connect_success_total 18207
telemt_upstream_connect_attempts_per_request{bucket="1"} 18207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7939
telemt_me_keepalive_timeout_total 259
telemt_me_reconnect_attempts_total 5141
telemt_me_reconnect_success_total 5116
telemt_me_reader_eof_total 5357
telemt_me_idle_close_by_peer_total 5357
telemt_me_route_drop_no_conn_total 184136
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 113
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 377
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 5
telemt_pool_force_close_total 269
telemt_me_writer_removed_unexpected_total 5363
telemt_me_writer_restored_same_endpoint_total 5115
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 322899
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 5162853000 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 113780985296 (105.97 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 27434.7 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 511789
telemt_connections_bad_total 11236
telemt_handshake_timeouts_total 5481
telemt_upstream_connect_attempt_total 11522
telemt_upstream_connect_success_total 11501
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5285
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 189
telemt_me_reconnect_attempts_total 1799
telemt_me_reconnect_success_total 1778
telemt_me_reader_eof_total 1879
telemt_me_idle_close_by_peer_total 1878
telemt_me_route_drop_no_conn_total 235228
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 977
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 625
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 8
telemt_pool_force_close_total 297
telemt_pool_stale_pick_total 293
telemt_me_writer_removed_unexpected_total 1883
telemt_me_writer_restored_same_endpoint_total 1775
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 469022
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 20962762324 (19.52 GB)
telemt_user_octets_to_client{user="hello"} 220203673116 (205.08 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 83
```