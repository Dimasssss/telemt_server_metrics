# Server Metrics 2026-03-11 18:15:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 100123.0 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2538242
telemt_connections_bad_total 48245
telemt_handshake_timeouts_total 56390
telemt_upstream_connect_attempt_total 21190
telemt_upstream_connect_success_total 21178
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5291
telemt_me_reconnect_attempts_total 33973
telemt_me_reconnect_success_total 16091
telemt_me_reader_eof_total 17410
telemt_me_idle_close_by_peer_total 17410
telemt_me_route_drop_no_conn_total 946703
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2321793
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11827
telemt_desync_full_logged_total 3259
telemt_desync_suppressed_total 8568
telemt_desync_frames_bucket_total{bucket="1_2"} 2920
telemt_desync_frames_bucket_total{bucket="3_10"} 4575
telemt_desync_frames_bucket_total{bucket="gt_10"} 4332
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16830
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16085
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 739
telemt_user_connections_total{user="hello"} 2320236
telemt_user_connections_current{user="hello"} 1079
telemt_user_octets_from_client{user="hello"} 34593865764 (32.22 GB)
telemt_user_octets_to_client{user="hello"} 655951695308 (610.90 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 100179.7 (27h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 951675
telemt_connections_bad_total 16367
telemt_handshake_timeouts_total 84638
telemt_upstream_connect_attempt_total 31221
telemt_upstream_connect_success_total 28254
telemt_upstream_connect_fail_total 2967
telemt_upstream_connect_attempts_per_request{bucket="1"} 31221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2043
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2967
telemt_me_keepalive_timeout_total 2814
telemt_me_reconnect_attempts_total 22363
telemt_me_reconnect_success_total 20253
telemt_me_reader_eof_total 21438
telemt_me_idle_close_by_peer_total 21435
telemt_me_route_drop_no_conn_total 359483
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 793265
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3122
telemt_desync_full_logged_total 1004
telemt_desync_suppressed_total 2118
telemt_desync_frames_bucket_total{bucket="1_2"} 971
telemt_desync_frames_bucket_total{bucket="3_10"} 1112
telemt_desync_frames_bucket_total{bucket="gt_10"} 1039
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 20535
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20230
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 795727
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 9606330742 (8.95 GB)
telemt_user_octets_to_client{user="hello"} 227051161360 (211.46 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 100179.6 (27h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1631021
telemt_connections_bad_total 10201
telemt_handshake_timeouts_total 132008
telemt_upstream_connect_attempt_total 25967
telemt_upstream_connect_success_total 25641
telemt_upstream_connect_fail_total 326
telemt_upstream_connect_attempts_per_request{bucket="1"} 25967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 326
telemt_me_keepalive_timeout_total 1943
telemt_me_reconnect_attempts_total 45497
telemt_me_reconnect_success_total 19490
telemt_me_reader_eof_total 21153
telemt_me_idle_close_by_peer_total 21153
telemt_me_route_drop_no_conn_total 593400
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1426506
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3889
telemt_desync_full_logged_total 1135
telemt_desync_suppressed_total 2754
telemt_desync_frames_bucket_total{bucket="1_2"} 921
telemt_desync_frames_bucket_total{bucket="3_10"} 1476
telemt_desync_frames_bucket_total{bucket="gt_10"} 1492
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20573
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 19478
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1083
telemt_user_connections_total{user="hello"} 1426191
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 17748414585 (16.53 GB)
telemt_user_octets_to_client{user="hello"} 434176592161 (404.36 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 100180.1 (27h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1162721
telemt_connections_bad_total 77991
telemt_handshake_timeouts_total 108050
telemt_upstream_connect_attempt_total 27041
telemt_upstream_connect_success_total 27041
telemt_upstream_connect_attempts_per_request{bucket="1"} 27041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1412
telemt_me_reconnect_attempts_total 26624
telemt_me_reconnect_success_total 22017
telemt_me_reader_eof_total 23392
telemt_me_idle_close_by_peer_total 23391
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 387024
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 942473
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1991
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 1232
telemt_desync_frames_bucket_total{bucket="1_2"} 719
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 587
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 22394
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21984
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 941737
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 11265325024 (10.49 GB)
telemt_user_octets_to_client{user="hello"} 287112055204 (267.39 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 4856.2 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85903
telemt_connections_bad_total 315
telemt_handshake_timeouts_total 520
telemt_upstream_connect_attempt_total 1441
telemt_upstream_connect_success_total 1441
telemt_upstream_connect_attempts_per_request{bucket="1"} 1441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 1151
telemt_me_reconnect_success_total 1141
telemt_me_reader_eof_total 1152
telemt_me_idle_close_by_peer_total 1152
telemt_me_route_drop_no_conn_total 28614
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80056
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 183
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1150
telemt_me_writer_restored_same_endpoint_total 1119
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 80049
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 6087873896 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 29547628236 (27.52 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 100
```