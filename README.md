# Server Metrics 2026-03-04 14:06:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 60936.1 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1107793
telemt_connections_bad_total 13919
telemt_handshake_timeouts_total 19664
telemt_upstream_connect_attempt_total 36634
telemt_upstream_connect_success_total 36466
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 36466
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 415
telemt_me_reconnect_attempts_total 7996
telemt_me_reconnect_success_total 7938
telemt_me_reader_eof_total 8195
telemt_me_idle_close_by_peer_total 8194
telemt_me_route_drop_no_conn_total 407805
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 240
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1917
telemt_desync_full_logged_total 637
telemt_desync_suppressed_total 1280
telemt_desync_frames_bucket_total{bucket="1_2"} 556
telemt_desync_frames_bucket_total{bucket="3_10"} 725
telemt_desync_frames_bucket_total{bucket="gt_10"} 636
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8195
telemt_me_writer_restored_same_endpoint_total 7916
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 879296
telemt_user_connections_current{user="hello"} 1245
telemt_user_octets_from_client{user="hello"} 10983561336 (10.23 GB)
telemt_user_octets_to_client{user="hello"} 297063562820 (276.66 GB)
telemt_user_unique_ips_current{user="hello"} 115
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 60932.6 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425134
telemt_connections_bad_total 3577
telemt_handshake_timeouts_total 29418
telemt_upstream_connect_attempt_total 109359
telemt_upstream_connect_success_total 107705
telemt_upstream_connect_fail_total 789
telemt_upstream_connect_attempts_per_request{bucket="1"} 107699
telemt_upstream_connect_attempts_per_request{bucket="2"} 795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 789
telemt_me_keepalive_timeout_total 1474
telemt_me_reconnect_attempts_total 59940
telemt_me_reconnect_success_total 59844
telemt_me_reader_eof_total 61424
telemt_me_idle_close_by_peer_total 61423
telemt_me_route_drop_no_conn_total 172446
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 256
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 837
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 578
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 331
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 61504
telemt_me_writer_restored_same_endpoint_total 59819
telemt_me_writer_removed_unexpected_minus_restored_total 1685
telemt_user_connections_total{user="hello"} 329912
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 4215176672 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 104714364296 (97.52 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 60930.8 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 837052
telemt_connections_bad_total 181274
telemt_handshake_timeouts_total 29175
telemt_upstream_connect_attempt_total 83403
telemt_upstream_connect_success_total 82882
telemt_upstream_connect_fail_total 251
telemt_upstream_connect_attempts_per_request{bucket="1"} 82881
telemt_upstream_connect_attempts_per_request{bucket="2"} 252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 251
telemt_me_keepalive_timeout_total 1089
telemt_me_reconnect_attempts_total 37956
telemt_me_reconnect_success_total 37857
telemt_me_reader_eof_total 39851
telemt_me_idle_close_by_peer_total 39847
telemt_me_route_drop_no_conn_total 305673
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 252
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1700
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 542
telemt_desync_frames_bucket_total{bucket="gt_10"} 606
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39863
telemt_me_writer_restored_same_endpoint_total 37835
telemt_me_writer_removed_unexpected_minus_restored_total 2028
telemt_user_connections_total{user="hello"} 588815
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 12405242244 (11.55 GB)
telemt_user_octets_to_client{user="hello"} 200017037980 (186.28 GB)
telemt_user_unique_ips_current{user="hello"} 79
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 7608.1 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96143
telemt_connections_bad_total 10268
telemt_handshake_timeouts_total 1930
telemt_upstream_connect_attempt_total 3807
telemt_upstream_connect_success_total 3807
telemt_upstream_connect_attempts_per_request{bucket="1"} 3807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1449
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 611
telemt_me_reconnect_success_total 625
telemt_me_reader_eof_total 622
telemt_me_idle_close_by_peer_total 622
telemt_me_route_drop_no_conn_total 35375
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 137
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 622
telemt_me_writer_restored_same_endpoint_total 604
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 82436
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 1367800852 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 50231827672 (46.78 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 7968.0 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139050
telemt_connections_bad_total 923
telemt_handshake_timeouts_total 2336
telemt_upstream_connect_attempt_total 5014
telemt_upstream_connect_success_total 4995
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4995
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1206
telemt_me_reconnect_success_total 1216
telemt_me_reader_eof_total 1239
telemt_me_idle_close_by_peer_total 1239
telemt_me_route_drop_no_conn_total 48612
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 378
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 239
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 1239
telemt_me_writer_restored_same_endpoint_total 1196
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 119511
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 1378738540 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 33488844016 (31.19 GB)
telemt_user_unique_ips_current{user="hello"} 53
```