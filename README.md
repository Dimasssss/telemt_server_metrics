# Server Metrics 2026-03-10 18:49:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 15763.7 (4h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512521
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 2582
telemt_upstream_connect_attempt_total 3173
telemt_upstream_connect_success_total 3164
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1583
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 294
telemt_me_reconnect_attempts_total 12762
telemt_me_reconnect_success_total 2304
telemt_me_reader_eof_total 2624
telemt_me_idle_close_by_peer_total 2624
telemt_me_route_drop_no_conn_total 214993
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 483591
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2505
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1817
telemt_desync_frames_bucket_total{bucket="1_2"} 661
telemt_desync_frames_bucket_total{bucket="3_10"} 969
telemt_desync_frames_bucket_total{bucket="gt_10"} 875
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2639
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2298
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 483505
telemt_user_connections_current{user="hello"} 1303
telemt_user_octets_from_client{user="hello"} 7053791960 (6.57 GB)
telemt_user_octets_to_client{user="hello"} 138951927036 (129.41 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 15820.3 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224552
telemt_connections_bad_total 1812
telemt_handshake_timeouts_total 16343
telemt_upstream_connect_attempt_total 8350
telemt_upstream_connect_success_total 5607
telemt_upstream_connect_fail_total 2743
telemt_upstream_connect_attempts_per_request{bucket="1"} 8350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1873
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2743
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2863
telemt_me_reconnect_success_total 2784
telemt_me_reader_eof_total 2888
telemt_me_idle_close_by_peer_total 2886
telemt_me_route_drop_no_conn_total 126402
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188559
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 728
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 506
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2814
telemt_me_writer_restored_same_endpoint_total 2763
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 190515
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 2089900350 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 45683720194 (42.55 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 15820.1 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371947
telemt_connections_bad_total 1074
telemt_handshake_timeouts_total 31835
telemt_upstream_connect_attempt_total 5012
telemt_upstream_connect_success_total 4933
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 5012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 6486
telemt_me_reconnect_success_total 3040
telemt_me_reader_eof_total 3244
telemt_me_idle_close_by_peer_total 3244
telemt_me_route_drop_no_conn_total 124022
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314653
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 983
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 707
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 408
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3201
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 3029
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 315610
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 4340652029 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 100480578537 (93.58 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 15820.7 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242196
telemt_connections_bad_total 15544
telemt_handshake_timeouts_total 21888
telemt_upstream_connect_attempt_total 4205
telemt_upstream_connect_success_total 4205
telemt_upstream_connect_attempts_per_request{bucket="1"} 4205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 3386
telemt_me_reconnect_success_total 3366
telemt_me_reader_eof_total 3485
telemt_me_idle_close_by_peer_total 3485
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 79905
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194624
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 534
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3397
telemt_me_writer_restored_same_endpoint_total 3354
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 194416
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 2896503068 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 55515770896 (51.70 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15820.5 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256233
telemt_connections_bad_total 802
telemt_handshake_timeouts_total 1788
telemt_upstream_connect_attempt_total 4768
telemt_upstream_connect_success_total 4751
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 3926
telemt_me_reconnect_success_total 3895
telemt_me_reader_eof_total 4012
telemt_me_idle_close_by_peer_total 4012
telemt_me_route_drop_no_conn_total 94984
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241731
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1365
telemt_desync_full_logged_total 487
telemt_desync_suppressed_total 878
telemt_desync_frames_bucket_total{bucket="1_2"} 549
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3945
telemt_me_writer_restored_same_endpoint_total 3895
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 241663
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 5090946340 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 76317392480 (71.08 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 77
```