# Server Metrics 2026-03-12 20:17:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 51503.5 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1783050
telemt_connections_bad_total 20721
telemt_handshake_timeouts_total 19253
telemt_upstream_connect_attempt_total 10049
telemt_upstream_connect_success_total 9990
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 10049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 580
telemt_me_reconnect_attempts_total 16217
telemt_me_reconnect_success_total 7369
telemt_me_reader_eof_total 7978
telemt_me_idle_close_by_peer_total 7977
telemt_me_route_drop_no_conn_total 702888
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1664449
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8208
telemt_desync_full_logged_total 2114
telemt_desync_suppressed_total 6094
telemt_desync_frames_bucket_total{bucket="1_2"} 2147
telemt_desync_frames_bucket_total{bucket="3_10"} 2959
telemt_desync_frames_bucket_total{bucket="gt_10"} 3102
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7752
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7356
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 1663935
telemt_user_connections_current{user="hello"} 1157
telemt_user_octets_from_client{user="hello"} 25666252972 (23.90 GB)
telemt_user_octets_to_client{user="hello"} 573723024156 (534.32 GB)
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 81124.0 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 753064
telemt_connections_bad_total 10679
telemt_handshake_timeouts_total 30233
telemt_upstream_connect_attempt_total 20552
telemt_upstream_connect_success_total 20523
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3380
telemt_me_reconnect_attempts_total 14883
telemt_me_reconnect_success_total 14794
telemt_me_reader_eof_total 15725
telemt_me_idle_close_by_peer_total 15725
telemt_me_route_drop_no_conn_total 241744
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 679289
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2930
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 2034
telemt_desync_frames_bucket_total{bucket="1_2"} 1131
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14947
telemt_me_writer_restored_same_endpoint_total 14785
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 681160
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 11555287668 (10.76 GB)
telemt_user_octets_to_client{user="hello"} 258028169623 (240.31 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 81123.7 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1555339
telemt_connections_bad_total 7448
telemt_handshake_timeouts_total 106323
telemt_upstream_connect_attempt_total 19077
telemt_upstream_connect_success_total 19071
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8739
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1202
telemt_me_reconnect_attempts_total 15876
telemt_me_reconnect_success_total 14628
telemt_me_reader_eof_total 15438
telemt_me_idle_close_by_peer_total 15437
telemt_me_route_drop_no_conn_total 514152
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1197976
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4791
telemt_desync_full_logged_total 1478
telemt_desync_suppressed_total 3313
telemt_desync_frames_bucket_total{bucket="1_2"} 759
telemt_desync_frames_bucket_total{bucket="3_10"} 1736
telemt_desync_frames_bucket_total{bucket="gt_10"} 2296
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 14766
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14587
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 1197585
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 18947434912 (17.65 GB)
telemt_user_octets_to_client{user="hello"} 446104995585 (415.47 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 81124.3 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 955253
telemt_connections_bad_total 12968
telemt_handshake_timeouts_total 70514
telemt_upstream_connect_attempt_total 20737
telemt_upstream_connect_success_total 20655
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 20737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 1667
telemt_me_reconnect_attempts_total 24304
telemt_me_reconnect_success_total 16578
telemt_me_reader_eof_total 17705
telemt_me_idle_close_by_peer_total 17705
telemt_me_route_drop_no_conn_total 340289
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 828239
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1749
telemt_desync_full_logged_total 586
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 491
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 16953
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16557
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 827589
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 12928349656 (12.04 GB)
telemt_user_octets_to_client{user="hello"} 339962000920 (316.61 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 81124.0 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1073408
telemt_connections_bad_total 12365
telemt_handshake_timeouts_total 8881
telemt_upstream_connect_attempt_total 25324
telemt_upstream_connect_success_total 25014
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 25324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12119
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 31957
telemt_me_reconnect_success_total 20919
telemt_me_reader_eof_total 21958
telemt_me_idle_close_by_peer_total 21958
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 401821
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 984730
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3690
telemt_desync_full_logged_total 1290
telemt_desync_suppressed_total 2400
telemt_desync_frames_bucket_total{bucket="1_2"} 1052
telemt_desync_frames_bucket_total{bucket="3_10"} 1223
telemt_desync_frames_bucket_total{bucket="gt_10"} 1415
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 21502
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20875
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 984599
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 12304480728 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 343178711552 (319.61 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 64
```