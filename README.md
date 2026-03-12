# Server Metrics 2026-03-12 18:34:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 45374.9 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1623699
telemt_connections_bad_total 20490
telemt_handshake_timeouts_total 15032
telemt_upstream_connect_attempt_total 9042
telemt_upstream_connect_success_total 8991
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 566
telemt_me_reconnect_attempts_total 15519
telemt_me_reconnect_success_total 6674
telemt_me_reader_eof_total 7229
telemt_me_idle_close_by_peer_total 7228
telemt_me_route_drop_no_conn_total 634745
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1520714
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7756
telemt_desync_full_logged_total 1970
telemt_desync_suppressed_total 5786
telemt_desync_frames_bucket_total{bucket="1_2"} 2012
telemt_desync_frames_bucket_total{bucket="3_10"} 2818
telemt_desync_frames_bucket_total{bucket="gt_10"} 2926
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7044
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6661
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 1520203
telemt_user_connections_current{user="hello"} 1408
telemt_user_octets_from_client{user="hello"} 23572503116 (21.95 GB)
telemt_user_octets_to_client{user="hello"} 510663215472 (475.59 GB)
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 74995.3 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 698361
telemt_connections_bad_total 9086
telemt_handshake_timeouts_total 29412
telemt_upstream_connect_attempt_total 19246
telemt_upstream_connect_success_total 19217
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3363
telemt_me_reconnect_attempts_total 13879
telemt_me_reconnect_success_total 13794
telemt_me_reader_eof_total 14668
telemt_me_idle_close_by_peer_total 14668
telemt_me_route_drop_no_conn_total 222750
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 628726
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2764
telemt_desync_full_logged_total 847
telemt_desync_suppressed_total 1917
telemt_desync_frames_bucket_total{bucket="1_2"} 1102
telemt_desync_frames_bucket_total{bucket="3_10"} 906
telemt_desync_frames_bucket_total{bucket="gt_10"} 756
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 13941
telemt_me_writer_restored_same_endpoint_total 13785
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 630606
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 9621879932 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 237177916091 (220.89 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 74995.2 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1447699
telemt_connections_bad_total 6996
telemt_handshake_timeouts_total 100222
telemt_upstream_connect_attempt_total 17877
telemt_upstream_connect_success_total 17872
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1183
telemt_me_reconnect_attempts_total 14977
telemt_me_reconnect_success_total 13733
telemt_me_reader_eof_total 14481
telemt_me_idle_close_by_peer_total 14480
telemt_me_route_drop_no_conn_total 476494
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1105873
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4663
telemt_desync_full_logged_total 1440
telemt_desync_suppressed_total 3223
telemt_desync_frames_bucket_total{bucket="1_2"} 726
telemt_desync_frames_bucket_total{bucket="3_10"} 1689
telemt_desync_frames_bucket_total{bucket="gt_10"} 2248
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 13856
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13692
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 1105736
telemt_user_connections_current{user="hello"} 941
telemt_user_octets_from_client{user="hello"} 16651137820 (15.51 GB)
telemt_user_octets_to_client{user="hello"} 403001964669 (375.32 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 74995.7 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 881814
telemt_connections_bad_total 12270
telemt_handshake_timeouts_total 65433
telemt_upstream_connect_attempt_total 19475
telemt_upstream_connect_success_total 19399
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 19475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1626
telemt_me_reconnect_attempts_total 23351
telemt_me_reconnect_success_total 15628
telemt_me_reader_eof_total 16694
telemt_me_idle_close_by_peer_total 16694
telemt_me_route_drop_no_conn_total 311224
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762174
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1735
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1154
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 574
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 15995
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15607
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 367
telemt_user_connections_total{user="hello"} 761537
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 9275245648 (8.64 GB)
telemt_user_octets_to_client{user="hello"} 309116623952 (287.89 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 74995.7 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 988002
telemt_connections_bad_total 11470
telemt_handshake_timeouts_total 8161
telemt_upstream_connect_attempt_total 23609
telemt_upstream_connect_success_total 23328
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 23609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 1380
telemt_me_reconnect_attempts_total 30573
telemt_me_reconnect_success_total 19539
telemt_me_reader_eof_total 20538
telemt_me_idle_close_by_peer_total 20538
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 367201
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 906841
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3471
telemt_desync_full_logged_total 1201
telemt_desync_suppressed_total 2270
telemt_desync_frames_bucket_total{bucket="1_2"} 974
telemt_desync_frames_bucket_total{bucket="3_10"} 1167
telemt_desync_frames_bucket_total{bucket="gt_10"} 1330
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 20103
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19495
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 564
telemt_user_connections_total{user="hello"} 906719
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 11173837184 (10.41 GB)
telemt_user_octets_to_client{user="hello"} 301169186396 (280.49 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 98
```