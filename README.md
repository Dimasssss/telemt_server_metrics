# Server Metrics 2026-03-13 05:07:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 83330.5 (23h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2246215
telemt_connections_bad_total 32407
telemt_handshake_timeouts_total 23538
telemt_upstream_connect_attempt_total 16431
telemt_upstream_connect_success_total 16339
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 21057
telemt_me_reconnect_success_total 12190
telemt_me_reader_eof_total 13156
telemt_me_idle_close_by_peer_total 13155
telemt_me_route_drop_no_conn_total 856427
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2065614
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9118
telemt_desync_full_logged_total 2358
telemt_desync_suppressed_total 6760
telemt_desync_frames_bucket_total{bucket="1_2"} 2383
telemt_desync_frames_bucket_total{bucket="3_10"} 3309
telemt_desync_frames_bucket_total{bucket="gt_10"} 3426
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 12637
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12177
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 2065035
telemt_user_connections_current{user="hello"} 1117
telemt_user_octets_from_client{user="hello"} 29976557396 (27.92 GB)
telemt_user_octets_to_client{user="hello"} 711935103712 (663.04 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 112951.2 (31h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 912626
telemt_connections_bad_total 12358
telemt_handshake_timeouts_total 39962
telemt_upstream_connect_attempt_total 28630
telemt_upstream_connect_success_total 28599
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 28630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3536
telemt_me_reconnect_attempts_total 21450
telemt_me_reconnect_success_total 21333
telemt_me_reader_eof_total 22743
telemt_me_idle_close_by_peer_total 22743
telemt_me_route_drop_no_conn_total 290575
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822414
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3251
telemt_desync_full_logged_total 1024
telemt_desync_suppressed_total 2227
telemt_desync_frames_bucket_total{bucket="1_2"} 1297
telemt_desync_frames_bucket_total{bucket="3_10"} 1063
telemt_desync_frames_bucket_total{bucket="gt_10"} 891
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 21543
telemt_me_writer_restored_same_endpoint_total 21324
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 824309
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 13218211376 (12.31 GB)
telemt_user_octets_to_client{user="hello"} 315611309531 (293.94 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 112951.1 (31h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1881913
telemt_connections_bad_total 18551
telemt_handshake_timeouts_total 123714
telemt_upstream_connect_attempt_total 26313
telemt_upstream_connect_success_total 26303
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12400
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1643
telemt_me_reconnect_attempts_total 21598
telemt_me_reconnect_success_total 20330
telemt_me_reader_eof_total 21534
telemt_me_idle_close_by_peer_total 21533
telemt_me_route_drop_no_conn_total 606403
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1485459
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5154
telemt_desync_full_logged_total 1577
telemt_desync_suppressed_total 3577
telemt_desync_frames_bucket_total{bucket="1_2"} 831
telemt_desync_frames_bucket_total{bucket="3_10"} 1860
telemt_desync_frames_bucket_total{bucket="gt_10"} 2463
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 20524
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20289
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 1484958
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 25561961992 (23.81 GB)
telemt_user_octets_to_client{user="hello"} 526499770889 (490.34 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 112951.4 (31h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1160219
telemt_connections_bad_total 13217
telemt_handshake_timeouts_total 75356
telemt_upstream_connect_attempt_total 38725
telemt_upstream_connect_success_total 36440
telemt_upstream_connect_fail_total 2148
telemt_upstream_connect_attempts_per_request{bucket="1"} 38451
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2147
telemt_me_keepalive_timeout_total 11396
telemt_me_reconnect_attempts_total 33884
telemt_me_reconnect_success_total 24950
telemt_me_reader_eof_total 26927
telemt_me_idle_close_by_peer_total 26920
telemt_me_route_drop_no_conn_total 413159
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 999023
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1975
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1325
telemt_desync_frames_bucket_total{bucket="1_2"} 549
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 25398
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24926
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 1004205
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 15314926241 (14.26 GB)
telemt_user_octets_to_client{user="hello"} 395451799462 (368.29 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 112951.3 (31h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1294329
telemt_connections_bad_total 12922
telemt_handshake_timeouts_total 10369
telemt_upstream_connect_attempt_total 35684
telemt_upstream_connect_success_total 35254
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 35684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 1957
telemt_me_reconnect_attempts_total 43364
telemt_me_reconnect_success_total 29631
telemt_me_reader_eof_total 31131
telemt_me_idle_close_by_peer_total 31131
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 479102
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1198177
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4351
telemt_desync_full_logged_total 1567
telemt_desync_suppressed_total 2784
telemt_desync_frames_bucket_total{bucket="1_2"} 1314
telemt_desync_frames_bucket_total{bucket="3_10"} 1418
telemt_desync_frames_bucket_total{bucket="gt_10"} 1619
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 30394
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29580
telemt_me_writer_restored_fallback_total 51
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 1198034
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 14542143512 (13.54 GB)
telemt_user_octets_to_client{user="hello"} 407186502620 (379.22 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 79
```