# Server Metrics 2026-03-11 16:18:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 93075.7 (25h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2316988
telemt_connections_bad_total 40443
telemt_handshake_timeouts_total 53791
telemt_upstream_connect_attempt_total 19504
telemt_upstream_connect_success_total 19492
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5008
telemt_me_reconnect_attempts_total 32643
telemt_me_reconnect_success_total 14769
telemt_me_reader_eof_total 16021
telemt_me_idle_close_by_peer_total 16021
telemt_me_route_drop_no_conn_total 860005
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2119258
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11001
telemt_desync_full_logged_total 3004
telemt_desync_suppressed_total 7997
telemt_desync_frames_bucket_total{bucket="1_2"} 2720
telemt_desync_frames_bucket_total{bucket="3_10"} 4247
telemt_desync_frames_bucket_total{bucket="gt_10"} 4034
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 15490
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14763
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 721
telemt_user_connections_total{user="hello"} 2117715
telemt_user_connections_current{user="hello"} 1395
telemt_user_octets_from_client{user="hello"} 28617506512 (26.65 GB)
telemt_user_octets_to_client{user="hello"} 598131121988 (557.05 GB)
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 93132.5 (25h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 863254
telemt_connections_bad_total 14827
telemt_handshake_timeouts_total 64971
telemt_upstream_connect_attempt_total 29373
telemt_upstream_connect_success_total 26415
telemt_upstream_connect_fail_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 29373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2958
telemt_me_keepalive_timeout_total 2635
telemt_me_reconnect_attempts_total 20878
telemt_me_reconnect_success_total 18783
telemt_me_reader_eof_total 19890
telemt_me_idle_close_by_peer_total 19887
telemt_me_route_drop_no_conn_total 334522
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728501
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2941
telemt_desync_full_logged_total 937
telemt_desync_suppressed_total 2004
telemt_desync_frames_bucket_total{bucket="1_2"} 907
telemt_desync_frames_bucket_total{bucket="3_10"} 1054
telemt_desync_frames_bucket_total{bucket="gt_10"} 980
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19053
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18760
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 730961
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 8370763978 (7.80 GB)
telemt_user_octets_to_client{user="hello"} 206880353140 (192.67 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 93132.4 (25h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1484350
telemt_connections_bad_total 8911
telemt_handshake_timeouts_total 125274
telemt_upstream_connect_attempt_total 24159
telemt_upstream_connect_success_total 23853
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 24159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_keepalive_timeout_total 1696
telemt_me_reconnect_attempts_total 41826
telemt_me_reconnect_success_total 18074
telemt_me_reader_eof_total 19621
telemt_me_idle_close_by_peer_total 19621
telemt_me_route_drop_no_conn_total 542948
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1296419
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3413
telemt_desync_full_logged_total 1011
telemt_desync_suppressed_total 2402
telemt_desync_frames_bucket_total{bucket="1_2"} 850
telemt_desync_frames_bucket_total{bucket="3_10"} 1288
telemt_desync_frames_bucket_total{bucket="gt_10"} 1275
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 19061
telemt_me_refill_failed_total 737
telemt_me_writer_restored_same_endpoint_total 18062
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 987
telemt_user_connections_total{user="hello"} 1296131
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 15714161413 (14.63 GB)
telemt_user_octets_to_client{user="hello"} 393382180309 (366.37 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 93132.9 (25h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1070789
telemt_connections_bad_total 77973
telemt_handshake_timeouts_total 103585
telemt_upstream_connect_attempt_total 25015
telemt_upstream_connect_success_total 25015
telemt_upstream_connect_attempts_per_request{bucket="1"} 25015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1083
telemt_me_reconnect_attempts_total 21439
telemt_me_reconnect_success_total 20363
telemt_me_reader_eof_total 21579
telemt_me_idle_close_by_peer_total 21578
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 350902
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 857181
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1778
telemt_desync_full_logged_total 683
telemt_desync_suppressed_total 1095
telemt_desync_frames_bucket_total{bucket="1_2"} 645
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20608
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 20332
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 856497
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 10293686640 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 253000716148 (235.63 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 93132.5 (25h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1179989
telemt_connections_bad_total 6947
telemt_handshake_timeouts_total 11774
telemt_upstream_connect_attempt_total 25420
telemt_upstream_connect_success_total 25306
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 25420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12176
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 2110
telemt_me_reconnect_attempts_total 24601
telemt_me_reconnect_success_total 20506
telemt_me_reader_eof_total 21614
telemt_me_idle_close_by_peer_total 21614
telemt_me_route_drop_no_conn_total 421524
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1074469
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4185
telemt_desync_full_logged_total 1495
telemt_desync_suppressed_total 2690
telemt_desync_frames_bucket_total{bucket="1_2"} 1384
telemt_desync_frames_bucket_total{bucket="3_10"} 1567
telemt_desync_frames_bucket_total{bucket="gt_10"} 1234
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20900
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20506
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 1074170
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 20245003359 (18.85 GB)
telemt_user_octets_to_client{user="hello"} 373575834174 (347.92 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 108
```