# Server Metrics 2026-03-15 07:36:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 33730.7 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 609489
telemt_connections_bad_total 20559
telemt_handshake_timeouts_total 4124
telemt_upstream_connect_attempt_total 7073
telemt_upstream_connect_success_total 7047
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 7073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 5382
telemt_me_reconnect_success_total 5354
telemt_me_reader_eof_total 5663
telemt_me_idle_close_by_peer_total 5663
telemt_me_route_drop_no_conn_total 190948
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 515477
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1423
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 975
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 510
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5424
telemt_me_writer_restored_same_endpoint_total 5343
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 515476
telemt_user_connections_current{user="hello"} 1714
telemt_user_octets_from_client{user="hello"} 6486556532 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 186093517132 (173.31 GB)
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 33731.2 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225597
telemt_connections_bad_total 18350
telemt_handshake_timeouts_total 8650
telemt_upstream_connect_attempt_total 9325
telemt_upstream_connect_success_total 9278
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 9325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4176
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7308
telemt_me_reconnect_success_total 7265
telemt_me_reader_eof_total 7694
telemt_me_idle_close_by_peer_total 7694
telemt_me_route_drop_no_conn_total 58932
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187016
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 471
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 236
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7303
telemt_me_writer_restored_same_endpoint_total 7257
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 187300
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 2957583419 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 68877765700 (64.15 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 33731.4 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414507
telemt_connections_bad_total 11891
telemt_handshake_timeouts_total 39786
telemt_upstream_connect_attempt_total 7635
telemt_upstream_connect_success_total 7602
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 5935
telemt_me_reconnect_success_total 5901
telemt_me_reader_eof_total 6250
telemt_me_idle_close_by_peer_total 6250
telemt_me_route_drop_no_conn_total 108244
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335980
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 647
telemt_desync_full_logged_total 260
telemt_desync_suppressed_total 387
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5969
telemt_me_writer_restored_same_endpoint_total 5882
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 335766
telemt_user_connections_current{user="hello"} 946
telemt_user_octets_from_client{user="hello"} 5107597884 (4.76 GB)
telemt_user_octets_to_client{user="hello"} 138744210896 (129.22 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 33731.2 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269561
telemt_connections_bad_total 45419
telemt_handshake_timeouts_total 18182
telemt_upstream_connect_attempt_total 10918
telemt_upstream_connect_success_total 10663
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 10918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 21607
telemt_me_reconnect_success_total 8971
telemt_me_reader_eof_total 9646
telemt_me_idle_close_by_peer_total 9646
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 67594
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199830
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 356
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 9439
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 8945
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 199831
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 1732971064 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 66862250704 (62.27 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 33731.9 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207781
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 2029
telemt_upstream_connect_attempt_total 7462
telemt_upstream_connect_success_total 7432
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 5768
telemt_me_reconnect_success_total 5741
telemt_me_reader_eof_total 6132
telemt_me_idle_close_by_peer_total 6132
telemt_me_route_drop_no_conn_total 63337
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194693
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 826
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 567
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 236
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5798
telemt_me_writer_restored_same_endpoint_total 5733
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 194700
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 2015880048 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 77470756472 (72.15 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 91
```