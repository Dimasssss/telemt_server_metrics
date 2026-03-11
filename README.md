# Server Metrics 2026-03-11 17:09:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 96138.2 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2414315
telemt_connections_bad_total 44532
telemt_handshake_timeouts_total 54385
telemt_upstream_connect_attempt_total 20190
telemt_upstream_connect_success_total 20178
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5107
telemt_me_reconnect_attempts_total 33196
telemt_me_reconnect_success_total 15320
telemt_me_reader_eof_total 16588
telemt_me_idle_close_by_peer_total 16588
telemt_me_route_drop_no_conn_total 897582
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2207671
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11390
telemt_desync_full_logged_total 3121
telemt_desync_suppressed_total 8269
telemt_desync_frames_bucket_total{bucket="1_2"} 2810
telemt_desync_frames_bucket_total{bucket="3_10"} 4397
telemt_desync_frames_bucket_total{bucket="gt_10"} 4183
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 16050
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15314
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 730
telemt_user_connections_total{user="hello"} 2206117
telemt_user_connections_current{user="hello"} 1402
telemt_user_octets_from_client{user="hello"} 29791653108 (27.75 GB)
telemt_user_octets_to_client{user="hello"} 622128610648 (579.40 GB)
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 96194.8 (26h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 905667
telemt_connections_bad_total 15799
telemt_handshake_timeouts_total 76487
telemt_upstream_connect_attempt_total 30280
telemt_upstream_connect_success_total 27320
telemt_upstream_connect_fail_total 2960
telemt_upstream_connect_attempts_per_request{bucket="1"} 30280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12258
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2960
telemt_me_keepalive_timeout_total 2667
telemt_me_reconnect_attempts_total 21649
telemt_me_reconnect_success_total 19546
telemt_me_reader_eof_total 20682
telemt_me_idle_close_by_peer_total 20679
telemt_me_route_drop_no_conn_total 345374
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 757671
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3036
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 2069
telemt_desync_frames_bucket_total{bucket="1_2"} 920
telemt_desync_frames_bucket_total{bucket="3_10"} 1090
telemt_desync_frames_bucket_total{bucket="gt_10"} 1026
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19821
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19523
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 760131
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 8733454350 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 215000262688 (200.23 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 96194.6 (26h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1547542
telemt_connections_bad_total 8995
telemt_handshake_timeouts_total 126322
telemt_upstream_connect_attempt_total 24898
telemt_upstream_connect_success_total 24580
telemt_upstream_connect_fail_total 318
telemt_upstream_connect_attempts_per_request{bucket="1"} 24898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 318
telemt_me_keepalive_timeout_total 1757
telemt_me_reconnect_attempts_total 42419
telemt_me_reconnect_success_total 18657
telemt_me_reader_eof_total 20221
telemt_me_idle_close_by_peer_total 20221
telemt_me_route_drop_no_conn_total 564735
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1352911
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3545
telemt_desync_full_logged_total 1042
telemt_desync_suppressed_total 2503
telemt_desync_frames_bucket_total{bucket="1_2"} 868
telemt_desync_frames_bucket_total{bucket="3_10"} 1339
telemt_desync_frames_bucket_total{bucket="gt_10"} 1338
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19656
telemt_me_refill_failed_total 737
telemt_me_writer_restored_same_endpoint_total 18645
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 999
telemt_user_connections_total{user="hello"} 1352605
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 16688551497 (15.54 GB)
telemt_user_octets_to_client{user="hello"} 410679275985 (382.47 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 96195.1 (26h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1110614
telemt_connections_bad_total 77987
telemt_handshake_timeouts_total 105851
telemt_upstream_connect_attempt_total 25880
telemt_upstream_connect_success_total 25880
telemt_upstream_connect_attempts_per_request{bucket="1"} 25880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1169
telemt_me_reconnect_attempts_total 23224
telemt_me_reconnect_success_total 21088
telemt_me_reader_eof_total 22369
telemt_me_idle_close_by_peer_total 22368
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 366495
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 893487
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1857
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1145
telemt_desync_frames_bucket_total{bucket="1_2"} 664
telemt_desync_frames_bucket_total{bucket="3_10"} 654
telemt_desync_frames_bucket_total{bucket="gt_10"} 539
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21379
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 21057
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 892765
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 10752476240 (10.01 GB)
telemt_user_octets_to_client{user="hello"} 269186722152 (250.70 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 871.2 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16988
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 170
telemt_upstream_connect_success_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 102
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 65
telemt_me_idle_close_by_peer_total 65
telemt_me_route_drop_no_conn_total 4692
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15690
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_desync_total 26
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_restored_same_endpoint_total 80
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_user_connections_total{user="hello"} 15691
telemt_user_connections_current{user="hello"} 710
telemt_user_octets_from_client{user="hello"} 125757964 (119.93 MB)
telemt_user_octets_to_client{user="hello"} 4732307392 (4.41 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 104
```