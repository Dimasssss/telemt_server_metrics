# Server Metrics 2026-03-13 03:20:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 76902.5 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2131022
telemt_connections_bad_total 28001
telemt_handshake_timeouts_total 22854
telemt_upstream_connect_attempt_total 15252
telemt_upstream_connect_success_total 15168
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 15252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1294
telemt_me_reconnect_attempts_total 20187
telemt_me_reconnect_success_total 11325
telemt_me_reader_eof_total 12232
telemt_me_idle_close_by_peer_total 12231
telemt_me_route_drop_no_conn_total 818025
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1960768
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8764
telemt_desync_full_logged_total 2279
telemt_desync_suppressed_total 6485
telemt_desync_frames_bucket_total{bucket="1_2"} 2309
telemt_desync_frames_bucket_total{bucket="3_10"} 3161
telemt_desync_frames_bucket_total{bucket="gt_10"} 3294
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11759
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11312
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 1960219
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 28547653124 (26.59 GB)
telemt_user_octets_to_client{user="hello"} 678084714944 (631.52 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 106522.9 (29h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 868100
telemt_connections_bad_total 11843
telemt_handshake_timeouts_total 36396
telemt_upstream_connect_attempt_total 27182
telemt_upstream_connect_success_total 27153
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3461
telemt_me_reconnect_attempts_total 20304
telemt_me_reconnect_success_total 20194
telemt_me_reader_eof_total 21522
telemt_me_idle_close_by_peer_total 21522
telemt_me_route_drop_no_conn_total 278737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 784241
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3107
telemt_desync_full_logged_total 976
telemt_desync_suppressed_total 2131
telemt_desync_frames_bucket_total{bucket="1_2"} 1257
telemt_desync_frames_bucket_total{bucket="3_10"} 1008
telemt_desync_frames_bucket_total{bucket="gt_10"} 842
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 20389
telemt_me_writer_restored_same_endpoint_total 20185
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 786145
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 12547728256 (11.69 GB)
telemt_user_octets_to_client{user="hello"} 300801680163 (280.14 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 106522.7 (29h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1797897
telemt_connections_bad_total 10717
telemt_handshake_timeouts_total 119912
telemt_upstream_connect_attempt_total 24871
telemt_upstream_connect_success_total 24861
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1620
telemt_me_reconnect_attempts_total 20459
telemt_me_reconnect_success_total 19194
telemt_me_reader_eof_total 20336
telemt_me_idle_close_by_peer_total 20335
telemt_me_route_drop_no_conn_total 584255
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1417114
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5047
telemt_desync_full_logged_total 1544
telemt_desync_suppressed_total 3503
telemt_desync_frames_bucket_total{bucket="1_2"} 807
telemt_desync_frames_bucket_total{bucket="3_10"} 1825
telemt_desync_frames_bucket_total{bucket="gt_10"} 2415
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 19374
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19153
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 1416708
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 24479006608 (22.80 GB)
telemt_user_octets_to_client{user="hello"} 508279252641 (473.37 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 106523.2 (29h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1120137
telemt_connections_bad_total 13144
telemt_handshake_timeouts_total 74076
telemt_upstream_connect_attempt_total 37115
telemt_upstream_connect_success_total 34835
telemt_upstream_connect_fail_total 2143
telemt_upstream_connect_attempts_per_request{bucket="1"} 36841
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2142
telemt_me_keepalive_timeout_total 11374
telemt_me_reconnect_attempts_total 32581
telemt_me_reconnect_success_total 23654
telemt_me_reader_eof_total 25542
telemt_me_idle_close_by_peer_total 25535
telemt_me_route_drop_no_conn_total 397214
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 961159
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1906
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24087
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23630
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 966329
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 14671024281 (13.66 GB)
telemt_user_octets_to_client{user="hello"} 380121006422 (354.02 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 106523.0 (29h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1240293
telemt_connections_bad_total 12650
telemt_handshake_timeouts_total 9643
telemt_upstream_connect_attempt_total 33538
telemt_upstream_connect_success_total 33129
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 33538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_keepalive_timeout_total 1904
telemt_me_reconnect_attempts_total 41546
telemt_me_reconnect_success_total 27816
telemt_me_reader_eof_total 29276
telemt_me_idle_close_by_peer_total 29276
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 462400
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1147325
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4251
telemt_desync_full_logged_total 1516
telemt_desync_suppressed_total 2735
telemt_desync_frames_bucket_total{bucket="1_2"} 1283
telemt_desync_frames_bucket_total{bucket="3_10"} 1396
telemt_desync_frames_bucket_total{bucket="gt_10"} 1572
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 28564
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27767
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 748
telemt_user_connections_total{user="hello"} 1147180
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 14173963256 (13.20 GB)
telemt_user_octets_to_client{user="hello"} 396164396428 (368.96 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 48
```