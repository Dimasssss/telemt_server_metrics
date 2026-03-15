# Server Metrics 2026-03-15 13:34:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 55183.3 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1649121
telemt_connections_bad_total 96303
telemt_handshake_timeouts_total 15922
telemt_upstream_connect_attempt_total 11023
telemt_upstream_connect_success_total 10974
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 13076
telemt_me_reconnect_success_total 8189
telemt_me_reader_eof_total 8777
telemt_me_idle_close_by_peer_total 8777
telemt_me_route_drop_no_conn_total 559558
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1388442
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5159
telemt_desync_full_logged_total 1447
telemt_desync_suppressed_total 3712
telemt_desync_frames_bucket_total{bucket="1_2"} 1321
telemt_desync_frames_bucket_total{bucket="3_10"} 2006
telemt_desync_frames_bucket_total{bucket="gt_10"} 1832
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8470
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8178
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 1388095
telemt_user_connections_current{user="hello"} 2397
telemt_user_octets_from_client{user="hello"} 19386249840 (18.05 GB)
telemt_user_octets_to_client{user="hello"} 555680959844 (517.52 GB)
telemt_user_unique_ips_current{user="hello"} 678
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 55184.2 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662731
telemt_connections_bad_total 34949
telemt_handshake_timeouts_total 47785
telemt_upstream_connect_attempt_total 14265
telemt_upstream_connect_success_total 14195
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6436
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 11161
telemt_me_reconnect_success_total 11078
telemt_me_reader_eof_total 11712
telemt_me_idle_close_by_peer_total 11712
telemt_me_route_drop_no_conn_total 166297
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502164
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1938
telemt_desync_full_logged_total 667
telemt_desync_suppressed_total 1271
telemt_desync_frames_bucket_total{bucket="1_2"} 726
telemt_desync_frames_bucket_total{bucket="3_10"} 703
telemt_desync_frames_bucket_total{bucket="gt_10"} 509
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11210
telemt_me_writer_restored_same_endpoint_total 11066
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 502433
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 7083108563 (6.60 GB)
telemt_user_octets_to_client{user="hello"} 190763245016 (177.66 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 55184.2 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1379428
telemt_connections_bad_total 42914
telemt_handshake_timeouts_total 142878
telemt_upstream_connect_attempt_total 12265
telemt_upstream_connect_success_total 12209
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10659
telemt_me_reconnect_success_total 9407
telemt_me_reader_eof_total 9976
telemt_me_idle_close_by_peer_total 9976
telemt_me_route_drop_no_conn_total 390589
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 887694
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2259
telemt_desync_full_logged_total 828
telemt_desync_suppressed_total 1431
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 856
telemt_desync_frames_bucket_total{bucket="gt_10"} 891
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9570
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9388
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 884177
telemt_user_connections_current{user="hello"} 1244
telemt_user_octets_from_client{user="hello"} 12783339412 (11.91 GB)
telemt_user_octets_to_client{user="hello"} 323140233280 (300.95 GB)
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 55184.1 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672775
telemt_connections_bad_total 69487
telemt_handshake_timeouts_total 36633
telemt_upstream_connect_attempt_total 78701
telemt_upstream_connect_success_total 78266
telemt_upstream_connect_fail_total 434
telemt_upstream_connect_attempts_per_request{bucket="1"} 78700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 434
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 46702
telemt_me_reconnect_success_total 11774
telemt_me_reader_eof_total 13198
telemt_me_idle_close_by_peer_total 13198
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 168431
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440777
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1158
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 865
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12976
telemt_me_refill_failed_total 1092
telemt_me_writer_restored_same_endpoint_total 11742
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1202
telemt_user_connections_total{user="hello"} 504363
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 9446052763 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 173879770805 (161.94 GB)
telemt_user_msgs_from_client{user="hello"} 1190918
telemt_user_msgs_to_client{user="hello"} 4373749
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 55185.3 (15h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 703975
telemt_connections_bad_total 9042
telemt_handshake_timeouts_total 14446
telemt_upstream_connect_attempt_total 12230
telemt_upstream_connect_success_total 12163
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 13053
telemt_me_reconnect_success_total 9383
telemt_me_reader_eof_total 10051
telemt_me_idle_close_by_peer_total 10051
telemt_me_route_drop_no_conn_total 175404
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571161
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2139
telemt_desync_full_logged_total 714
telemt_desync_suppressed_total 1425
telemt_desync_frames_bucket_total{bucket="1_2"} 630
telemt_desync_frames_bucket_total{bucket="3_10"} 847
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9609
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9375
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 571203
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 7199416328 (6.70 GB)
telemt_user_octets_to_client{user="hello"} 214852734100 (200.10 GB)
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 117
```