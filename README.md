# Server Metrics 2026-03-15 10:45:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 45072.7 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1115583
telemt_connections_bad_total 68063
telemt_handshake_timeouts_total 9027
telemt_upstream_connect_attempt_total 9073
telemt_upstream_connect_success_total 9034
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 9073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7999
telemt_me_reconnect_success_total 6775
telemt_me_reader_eof_total 7188
telemt_me_idle_close_by_peer_total 7188
telemt_me_route_drop_no_conn_total 371506
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 941207
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3522
telemt_desync_full_logged_total 990
telemt_desync_suppressed_total 2532
telemt_desync_frames_bucket_total{bucket="1_2"} 877
telemt_desync_frames_bucket_total{bucket="3_10"} 1371
telemt_desync_frames_bucket_total{bucket="gt_10"} 1274
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6909
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 6764
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 941202
telemt_user_connections_current{user="hello"} 2215
telemt_user_octets_from_client{user="hello"} 13377090464 (12.46 GB)
telemt_user_octets_to_client{user="hello"} 376585271572 (350.72 GB)
telemt_user_unique_ips_current{user="hello"} 600
telemt_user_unique_ips_recent_window{user="hello"} 319
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 45073.2 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437770
telemt_connections_bad_total 23978
telemt_handshake_timeouts_total 18165
telemt_upstream_connect_attempt_total 11978
telemt_upstream_connect_success_total 11914
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 11978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5361
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9388
telemt_me_reconnect_success_total 9330
telemt_me_reader_eof_total 9863
telemt_me_idle_close_by_peer_total 9863
telemt_me_route_drop_no_conn_total 111583
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346368
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1220
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 794
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 448
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9423
telemt_me_writer_restored_same_endpoint_total 9322
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 346653
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 5007079687 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 130370746700 (121.42 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 45073.2 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 837337
telemt_connections_bad_total 28040
telemt_handshake_timeouts_total 83349
telemt_upstream_connect_attempt_total 9959
telemt_upstream_connect_success_total 9916
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 7691
telemt_me_reconnect_success_total 7641
telemt_me_reader_eof_total 8092
telemt_me_idle_close_by_peer_total 8092
telemt_me_route_drop_no_conn_total 230345
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 608603
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1388
telemt_desync_full_logged_total 508
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 508
telemt_desync_frames_bucket_total{bucket="gt_10"} 577
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7743
telemt_me_writer_restored_same_endpoint_total 7622
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 608025
telemt_user_connections_current{user="hello"} 1163
telemt_user_octets_from_client{user="hello"} 8990282548 (8.37 GB)
telemt_user_octets_to_client{user="hello"} 240663638828 (224.14 GB)
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 45073.1 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455153
telemt_connections_bad_total 56796
telemt_handshake_timeouts_total 25983
telemt_upstream_connect_attempt_total 13477
telemt_upstream_connect_success_total 13134
telemt_upstream_connect_fail_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 13477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 343
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 31243
telemt_me_reconnect_success_total 10880
telemt_me_reader_eof_total 11842
telemt_me_idle_close_by_peer_total 11842
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 127174
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342146
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 607
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 11615
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 10848
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 735
telemt_user_connections_total{user="hello"} 342054
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 4070054532 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 108527008160 (101.07 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 45074.1 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 464617
telemt_connections_bad_total 6152
telemt_handshake_timeouts_total 7830
telemt_upstream_connect_attempt_total 9918
telemt_upstream_connect_success_total 9873
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7658
telemt_me_reconnect_success_total 7620
telemt_me_reader_eof_total 8105
telemt_me_idle_close_by_peer_total 8105
telemt_me_route_drop_no_conn_total 120965
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383856
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1489
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 436
telemt_desync_frames_bucket_total{bucket="3_10"} 615
telemt_desync_frames_bucket_total{bucket="gt_10"} 438
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7707
telemt_me_writer_restored_same_endpoint_total 7612
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 383870
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 4769184048 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 143450505700 (133.60 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 136
```