# Server Metrics 2026-03-11 04:39:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 51171.6 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 992214
telemt_connections_bad_total 10080
telemt_handshake_timeouts_total 29959
telemt_upstream_connect_attempt_total 10990
telemt_upstream_connect_success_total 10981
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 534
telemt_me_reconnect_attempts_total 20059
telemt_me_reconnect_success_total 8385
telemt_me_reader_eof_total 9135
telemt_me_idle_close_by_peer_total 9135
telemt_me_route_drop_no_conn_total 371926
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 894601
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4045
telemt_desync_full_logged_total 1137
telemt_desync_suppressed_total 2908
telemt_desync_frames_bucket_total{bucket="1_2"} 1140
telemt_desync_frames_bucket_total{bucket="3_10"} 1525
telemt_desync_frames_bucket_total{bucket="gt_10"} 1380
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8825
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8379
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 894321
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 11684642440 (10.88 GB)
telemt_user_octets_to_client{user="hello"} 263286409568 (245.20 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 51228.4 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391304
telemt_connections_bad_total 2532
telemt_handshake_timeouts_total 18921
telemt_upstream_connect_attempt_total 19281
telemt_upstream_connect_success_total 16384
telemt_upstream_connect_fail_total 2897
telemt_upstream_connect_attempts_per_request{bucket="1"} 19281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2897
telemt_me_keepalive_timeout_total 1777
telemt_me_reconnect_attempts_total 11691
telemt_me_reconnect_success_total 10873
telemt_me_reader_eof_total 11487
telemt_me_idle_close_by_peer_total 11485
telemt_me_route_drop_no_conn_total 186521
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336162
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1849
telemt_desync_full_logged_total 550
telemt_desync_suppressed_total 1299
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 11000
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10852
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 338434
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 3236567146 (3.01 GB)
telemt_user_octets_to_client{user="hello"} 80779391576 (75.23 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 51228.1 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 660273
telemt_connections_bad_total 5547
telemt_handshake_timeouts_total 36199
telemt_upstream_connect_attempt_total 13879
telemt_upstream_connect_success_total 13700
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 13879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 561
telemt_me_reconnect_attempts_total 21131
telemt_me_reconnect_success_total 10061
telemt_me_reader_eof_total 10878
telemt_me_idle_close_by_peer_total 10878
telemt_me_route_drop_no_conn_total 222705
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588650
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1631
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 573
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 10539
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10050
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 478
telemt_user_connections_total{user="hello"} 589518
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 7325582905 (6.82 GB)
telemt_user_octets_to_client{user="hello"} 178001743897 (165.78 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 51228.6 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504132
telemt_connections_bad_total 48226
telemt_handshake_timeouts_total 53063
telemt_upstream_connect_attempt_total 14818
telemt_upstream_connect_success_total 14818
telemt_upstream_connect_attempts_per_request{bucket="1"} 14818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 488
telemt_me_reconnect_attempts_total 13297
telemt_me_reconnect_success_total 12255
telemt_me_reader_eof_total 13010
telemt_me_idle_close_by_peer_total 13010
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 149625
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388691
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 826
telemt_desync_full_logged_total 335
telemt_desync_suppressed_total 491
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 12398
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12235
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 388349
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 4728009024 (4.40 GB)
telemt_user_octets_to_client{user="hello"} 105693946500 (98.44 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 51228.3 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527346
telemt_connections_bad_total 5827
telemt_handshake_timeouts_total 3404
telemt_upstream_connect_attempt_total 14819
telemt_upstream_connect_success_total 14757
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 14819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7092
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 555
telemt_me_reconnect_attempts_total 15935
telemt_me_reconnect_success_total 12154
telemt_me_reader_eof_total 12828
telemt_me_idle_close_by_peer_total 12828
telemt_me_route_drop_no_conn_total 170825
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 480323
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2402
telemt_desync_full_logged_total 938
telemt_desync_suppressed_total 1464
telemt_desync_frames_bucket_total{bucket="1_2"} 886
telemt_desync_frames_bucket_total{bucket="3_10"} 1018
telemt_desync_frames_bucket_total{bucket="gt_10"} 498
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12428
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12154
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 479941
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 8813655636 (8.21 GB)
telemt_user_octets_to_client{user="hello"} 169837261348 (158.17 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 62
```