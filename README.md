# Server Metrics 2026-03-12 10:29:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 16278.7 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532299
telemt_connections_bad_total 1467
telemt_handshake_timeouts_total 2895
telemt_upstream_connect_attempt_total 3185
telemt_upstream_connect_success_total 3164
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 287
telemt_me_reconnect_attempts_total 6193
telemt_me_reconnect_success_total 2307
telemt_me_reader_eof_total 2500
telemt_me_idle_close_by_peer_total 2500
telemt_me_route_drop_no_conn_total 183830
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 515738
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2453
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1841
telemt_desync_frames_bucket_total{bucket="1_2"} 622
telemt_desync_frames_bucket_total{bucket="3_10"} 902
telemt_desync_frames_bucket_total{bucket="gt_10"} 929
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2450
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2294
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 515603
telemt_user_connections_current{user="hello"} 1447
telemt_user_octets_from_client{user="hello"} 8124533700 (7.57 GB)
telemt_user_octets_to_client{user="hello"} 140154590216 (130.53 GB)
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 45899.1 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299180
telemt_connections_bad_total 3368
telemt_handshake_timeouts_total 8622
telemt_upstream_connect_attempt_total 11534
telemt_upstream_connect_success_total 11528
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 674
telemt_me_reconnect_attempts_total 9116
telemt_me_reconnect_success_total 9069
telemt_me_reader_eof_total 9635
telemt_me_idle_close_by_peer_total 9635
telemt_me_route_drop_no_conn_total 86730
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268135
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 529
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 317
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9144
telemt_me_writer_restored_same_endpoint_total 9060
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 268578
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 3717038363 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 97448883766 (90.76 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 45899.1 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 751191
telemt_connections_bad_total 3713
telemt_handshake_timeouts_total 54844
telemt_upstream_connect_attempt_total 11521
telemt_upstream_connect_success_total 11516
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 587
telemt_me_reconnect_attempts_total 8963
telemt_me_reconnect_success_total 8887
telemt_me_reader_eof_total 9337
telemt_me_idle_close_by_peer_total 9337
telemt_me_route_drop_no_conn_total 168306
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479504
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2146
telemt_desync_full_logged_total 641
telemt_desync_suppressed_total 1505
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 1125
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8899
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8846
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 479757
telemt_user_connections_current{user="hello"} 861
telemt_user_octets_from_client{user="hello"} 5669723240 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 155313121793 (144.65 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 45899.4 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385995
telemt_connections_bad_total 2472
telemt_handshake_timeouts_total 29149
telemt_upstream_connect_attempt_total 12370
telemt_upstream_connect_success_total 12320
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 12370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 842
telemt_me_reconnect_attempts_total 10080
telemt_me_reconnect_success_total 10043
telemt_me_reader_eof_total 10654
telemt_me_idle_close_by_peer_total 10654
telemt_me_route_drop_no_conn_total 130232
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325778
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 673
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 436
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10110
telemt_me_writer_restored_same_endpoint_total 10022
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 325598
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 3915729140 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 126413891856 (117.73 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 45899.1 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435888
telemt_connections_bad_total 469
telemt_handshake_timeouts_total 3275
telemt_upstream_connect_attempt_total 14807
telemt_upstream_connect_success_total 14634
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 14807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_timeout_total 627
telemt_me_reconnect_attempts_total 13871
telemt_me_reconnect_success_total 12347
telemt_me_reader_eof_total 12862
telemt_me_idle_close_by_peer_total 12862
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 140947
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410829
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1728
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 1156
telemt_desync_frames_bucket_total{bucket="1_2"} 508
telemt_desync_frames_bucket_total{bucket="3_10"} 598
telemt_desync_frames_bucket_total{bucket="gt_10"} 622
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 12515
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 12325
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 410754
telemt_user_connections_current{user="hello"} 785
telemt_user_octets_from_client{user="hello"} 4606816904 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 99184102524 (92.37 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 104
```