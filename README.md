# Server Metrics 2026-03-11 13:55:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 84493.8 (23h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2012047
telemt_connections_bad_total 27779
telemt_handshake_timeouts_total 51788
telemt_upstream_connect_attempt_total 17605
telemt_upstream_connect_success_total 17596
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 17605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 983
telemt_me_reconnect_attempts_total 26174
telemt_me_reconnect_success_total 13342
telemt_me_reader_eof_total 14397
telemt_me_idle_close_by_peer_total 14397
telemt_me_route_drop_no_conn_total 740382
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1839538
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9667
telemt_desync_full_logged_total 2619
telemt_desync_suppressed_total 7048
telemt_desync_frames_bucket_total{bucket="1_2"} 2385
telemt_desync_frames_bucket_total{bucket="3_10"} 3735
telemt_desync_frames_bucket_total{bucket="gt_10"} 3547
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13884
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 13336
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 1838048
telemt_user_connections_current{user="hello"} 1492
telemt_user_octets_from_client{user="hello"} 24682715644 (22.99 GB)
telemt_user_octets_to_client{user="hello"} 523147602604 (487.22 GB)
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 84550.5 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759549
telemt_connections_bad_total 13091
telemt_handshake_timeouts_total 51327
telemt_upstream_connect_attempt_total 27182
telemt_upstream_connect_success_total 24234
telemt_upstream_connect_fail_total 2948
telemt_upstream_connect_attempts_per_request{bucket="1"} 27182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2948
telemt_me_keepalive_timeout_total 2506
telemt_me_reconnect_attempts_total 17928
telemt_me_reconnect_success_total 17061
telemt_me_reader_eof_total 18031
telemt_me_idle_close_by_peer_total 18028
telemt_me_route_drop_no_conn_total 296661
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642245
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2796
telemt_desync_full_logged_total 886
telemt_desync_suppressed_total 1910
telemt_desync_frames_bucket_total{bucket="1_2"} 869
telemt_desync_frames_bucket_total{bucket="3_10"} 1018
telemt_desync_frames_bucket_total{bucket="gt_10"} 909
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17275
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 17038
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 644730
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 6867830522 (6.40 GB)
telemt_user_octets_to_client{user="hello"} 183065950008 (170.49 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 84550.5 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1312599
telemt_connections_bad_total 8357
telemt_handshake_timeouts_total 119890
telemt_upstream_connect_attempt_total 22438
telemt_upstream_connect_success_total 22167
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 22438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 901
telemt_me_reconnect_attempts_total 32956
telemt_me_reconnect_success_total 16848
telemt_me_reader_eof_total 18118
telemt_me_idle_close_by_peer_total 18118
telemt_me_route_drop_no_conn_total 461253
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1135612
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3013
telemt_desync_full_logged_total 893
telemt_desync_suppressed_total 2120
telemt_desync_frames_bucket_total{bucket="1_2"} 725
telemt_desync_frames_bucket_total{bucket="3_10"} 1137
telemt_desync_frames_bucket_total{bucket="gt_10"} 1151
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17576
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16837
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 728
telemt_user_connections_total{user="hello"} 1135770
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 13659489085 (12.72 GB)
telemt_user_octets_to_client{user="hello"} 339433039601 (316.12 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 84550.9 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 942653
telemt_connections_bad_total 77222
telemt_handshake_timeouts_total 89270
telemt_upstream_connect_attempt_total 22971
telemt_upstream_connect_success_total 22971
telemt_upstream_connect_attempts_per_request{bucket="1"} 22971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 950
telemt_me_reconnect_attempts_total 19832
telemt_me_reconnect_success_total 18761
telemt_me_reader_eof_total 19886
telemt_me_idle_close_by_peer_total 19885
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 304823
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 750542
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1605
telemt_desync_full_logged_total 626
telemt_desync_suppressed_total 979
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 565
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18991
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18733
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 749892
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 8664554620 (8.07 GB)
telemt_user_octets_to_client{user="hello"} 217717054908 (202.76 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 84550.5 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1032223
telemt_connections_bad_total 6823
telemt_handshake_timeouts_total 9395
telemt_upstream_connect_attempt_total 22932
telemt_upstream_connect_success_total 22833
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 22932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 979
telemt_me_reconnect_attempts_total 22570
telemt_me_reconnect_success_total 18496
telemt_me_reader_eof_total 19519
telemt_me_idle_close_by_peer_total 19519
telemt_me_route_drop_no_conn_total 365683
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 937654
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3725
telemt_desync_full_logged_total 1375
telemt_desync_suppressed_total 2350
telemt_desync_frames_bucket_total{bucket="1_2"} 1310
telemt_desync_frames_bucket_total{bucket="3_10"} 1403
telemt_desync_frames_bucket_total{bucket="gt_10"} 1012
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18861
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18496
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 365
telemt_user_connections_total{user="hello"} 937391
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 13669392039 (12.73 GB)
telemt_user_octets_to_client{user="hello"} 333194265414 (310.31 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 113
```