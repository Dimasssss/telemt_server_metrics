# Server Metrics 2026-03-15 08:32:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 37099.9 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 744132
telemt_connections_bad_total 30082
telemt_handshake_timeouts_total 5235
telemt_upstream_connect_attempt_total 7659
telemt_upstream_connect_success_total 7627
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5786
telemt_me_reconnect_success_total 5755
telemt_me_reader_eof_total 6089
telemt_me_idle_close_by_peer_total 6089
telemt_me_route_drop_no_conn_total 240029
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 631227
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1887
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1298
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 786
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5831
telemt_me_writer_restored_same_endpoint_total 5744
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 631217
telemt_user_connections_current{user="hello"} 1964
telemt_user_octets_from_client{user="hello"} 8466081144 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 235257406572 (219.10 GB)
telemt_user_unique_ips_current{user="hello"} 559
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 37100.7 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293173
telemt_connections_bad_total 18440
telemt_handshake_timeouts_total 12123
telemt_upstream_connect_attempt_total 10018
telemt_upstream_connect_success_total 9968
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 10018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7820
telemt_me_reconnect_success_total 7773
telemt_me_reader_eof_total 8236
telemt_me_idle_close_by_peer_total 8236
telemt_me_route_drop_no_conn_total 73698
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231315
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 865
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 575
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 276
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7829
telemt_me_writer_restored_same_endpoint_total 7765
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 231592
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 3389704359 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 85560391740 (79.68 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 37100.8 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504180
telemt_connections_bad_total 15307
telemt_handshake_timeouts_total 44950
telemt_upstream_connect_attempt_total 8291
telemt_upstream_connect_success_total 8254
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 6413
telemt_me_reconnect_success_total 6372
telemt_me_reader_eof_total 6753
telemt_me_idle_close_by_peer_total 6753
telemt_me_route_drop_no_conn_total 136341
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407374
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 813
telemt_desync_full_logged_total 316
telemt_desync_suppressed_total 497
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6451
telemt_me_writer_restored_same_endpoint_total 6353
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 406908
telemt_user_connections_current{user="hello"} 1180
telemt_user_octets_from_client{user="hello"} 6059864808 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 171082196720 (159.33 GB)
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 37100.7 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319556
telemt_connections_bad_total 48265
telemt_handshake_timeouts_total 21764
telemt_upstream_connect_attempt_total 11846
telemt_upstream_connect_success_total 11574
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 11846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 22342
telemt_me_reconnect_success_total 9699
telemt_me_reader_eof_total 10400
telemt_me_idle_close_by_peer_total 10400
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 84402
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238460
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 512
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 380
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10176
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 9670
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 477
telemt_user_connections_total{user="hello"} 238463
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 2100311944 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 78879414368 (73.46 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 37101.5 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278927
telemt_connections_bad_total 3668
telemt_handshake_timeouts_total 2843
telemt_upstream_connect_attempt_total 8252
telemt_upstream_connect_success_total 8218
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 8252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 6379
telemt_me_reconnect_success_total 6350
telemt_me_reader_eof_total 6777
telemt_me_idle_close_by_peer_total 6777
telemt_me_route_drop_no_conn_total 79149
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244514
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 977
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 659
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 398
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6414
telemt_me_writer_restored_same_endpoint_total 6342
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 244525
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 2691715724 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 95958780572 (89.37 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 109
```