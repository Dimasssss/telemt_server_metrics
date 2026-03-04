# Server Metrics 2026-03-04 10:56:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 49558.7 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 767057
telemt_connections_bad_total 11430
telemt_handshake_timeouts_total 9361
telemt_upstream_connect_attempt_total 31802
telemt_upstream_connect_success_total 31667
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 31667
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 349
telemt_me_reconnect_attempts_total 7076
telemt_me_reconnect_success_total 7031
telemt_me_reader_eof_total 7250
telemt_me_idle_close_by_peer_total 7250
telemt_me_route_drop_no_conn_total 300544
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1266
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 833
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 11
telemt_pool_force_close_total 451
telemt_me_writer_removed_unexpected_total 7250
telemt_me_writer_restored_same_endpoint_total 7010
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 625514
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 6954604532 (6.48 GB)
telemt_user_octets_to_client{user="hello"} 187273358084 (174.41 GB)
telemt_user_unique_ips_current{user="hello"} 84
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 49555.2 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297519
telemt_connections_bad_total 2784
telemt_handshake_timeouts_total 26988
telemt_upstream_connect_attempt_total 96103
telemt_upstream_connect_success_total 94689
telemt_upstream_connect_fail_total 669
telemt_upstream_connect_attempts_per_request{bucket="1"} 94683
telemt_upstream_connect_attempts_per_request{bucket="2"} 675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 669
telemt_me_keepalive_timeout_total 1361
telemt_me_reconnect_attempts_total 54715
telemt_me_reconnect_success_total 54629
telemt_me_reader_eof_total 56030
telemt_me_idle_close_by_peer_total 56029
telemt_me_route_drop_no_conn_total 133198
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 583
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 56110
telemt_me_writer_restored_same_endpoint_total 54604
telemt_me_writer_removed_unexpected_minus_restored_total 1506
telemt_user_connections_total{user="hello"} 233053
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 2762551892 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 76768052948 (71.50 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 49554.1 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593440
telemt_connections_bad_total 149728
telemt_handshake_timeouts_total 18083
telemt_upstream_connect_attempt_total 73928
telemt_upstream_connect_success_total 73491
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 73490
telemt_upstream_connect_attempts_per_request{bucket="2"} 210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 952
telemt_me_reconnect_attempts_total 34419
telemt_me_reconnect_success_total 34332
telemt_me_reader_eof_total 36177
telemt_me_idle_close_by_peer_total 36173
telemt_me_route_drop_no_conn_total 217503
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 206
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1021
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 650
telemt_desync_frames_bucket_total{bucket="1_2"} 316
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 36189
telemt_me_writer_restored_same_endpoint_total 34311
telemt_me_writer_removed_unexpected_minus_restored_total 1878
telemt_user_connections_total{user="hello"} 406952
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 5131906128 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 138669694764 (129.15 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 49552.9 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388271
telemt_connections_bad_total 26712
telemt_handshake_timeouts_total 66149
telemt_upstream_connect_attempt_total 36404
telemt_upstream_connect_success_total 36260
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 36260
telemt_upstream_connect_attempts_per_request{bucket="2"} 70
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13728
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 409
telemt_me_reconnect_attempts_total 7517
telemt_me_reconnect_success_total 7491
telemt_me_reader_eof_total 7638
telemt_me_idle_close_by_peer_total 7638
telemt_me_route_drop_no_conn_total 109208
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 211
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 13
telemt_pool_force_close_total 316
telemt_me_writer_removed_unexpected_total 7638
telemt_me_writer_restored_same_endpoint_total 7470
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 273504
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 3107517468 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 98363280136 (91.61 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 49551.8 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524944
telemt_connections_bad_total 6813
telemt_handshake_timeouts_total 132372
telemt_upstream_connect_attempt_total 70649
telemt_upstream_connect_success_total 70170
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 70170
telemt_upstream_connect_attempts_per_request{bucket="2"} 227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 918
telemt_me_reconnect_attempts_total 34139
telemt_me_reconnect_success_total 34107
telemt_me_reader_eof_total 35799
telemt_me_idle_close_by_peer_total 35798
telemt_me_route_drop_no_conn_total 164214
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 207
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 599
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 398
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35811
telemt_me_writer_restored_same_endpoint_total 34082
telemt_me_writer_removed_unexpected_minus_restored_total 1729
telemt_user_connections_total{user="hello"} 361846
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 4772840868 (4.45 GB)
telemt_user_octets_to_client{user="hello"} 96297779032 (89.68 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 56
```