# Server Metrics 2026-03-11 04:14:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 49647.1 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 955562
telemt_connections_bad_total 10072
telemt_handshake_timeouts_total 27120
telemt_upstream_connect_attempt_total 10706
telemt_upstream_connect_success_total 10697
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 529
telemt_me_reconnect_attempts_total 19818
telemt_me_reconnect_success_total 8145
telemt_me_reader_eof_total 8880
telemt_me_idle_close_by_peer_total 8880
telemt_me_route_drop_no_conn_total 363925
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 869541
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3957
telemt_desync_full_logged_total 1106
telemt_desync_suppressed_total 2851
telemt_desync_frames_bucket_total{bucket="1_2"} 1122
telemt_desync_frames_bucket_total{bucket="3_10"} 1491
telemt_desync_frames_bucket_total{bucket="gt_10"} 1344
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 8584
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8139
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 869262
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 11427228604 (10.64 GB)
telemt_user_octets_to_client{user="hello"} 256973594440 (239.33 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 49703.8 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383660
telemt_connections_bad_total 2531
telemt_handshake_timeouts_total 18838
telemt_upstream_connect_attempt_total 18866
telemt_upstream_connect_success_total 15968
telemt_upstream_connect_fail_total 2897
telemt_upstream_connect_attempts_per_request{bucket="1"} 18865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2897
telemt_me_keepalive_timeout_total 1774
telemt_me_reconnect_attempts_total 11319
telemt_me_reconnect_success_total 10500
telemt_me_reader_eof_total 11094
telemt_me_idle_close_by_peer_total 11092
telemt_me_route_drop_no_conn_total 184174
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329146
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1839
telemt_desync_full_logged_total 543
telemt_desync_suppressed_total 1296
telemt_desync_frames_bucket_total{bucket="1_2"} 563
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 10626
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10479
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 331417
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 3146778734 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 77844125800 (72.50 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 49703.6 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 645672
telemt_connections_bad_total 5546
telemt_handshake_timeouts_total 35895
telemt_upstream_connect_attempt_total 13472
telemt_upstream_connect_success_total 13297
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 13472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 556
telemt_me_reconnect_attempts_total 20772
telemt_me_reconnect_success_total 9702
telemt_me_reader_eof_total 10515
telemt_me_idle_close_by_peer_total 10515
telemt_me_route_drop_no_conn_total 218247
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 574839
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1629
telemt_desync_full_logged_total 481
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 10176
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9691
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 474
telemt_user_connections_total{user="hello"} 575730
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 7249734245 (6.75 GB)
telemt_user_octets_to_client{user="hello"} 175150740381 (163.12 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 49704.1 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490822
telemt_connections_bad_total 46834
telemt_handshake_timeouts_total 51108
telemt_upstream_connect_attempt_total 14450
telemt_upstream_connect_success_total 14450
telemt_upstream_connect_attempts_per_request{bucket="1"} 14450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 481
telemt_me_reconnect_attempts_total 12974
telemt_me_reconnect_success_total 11934
telemt_me_reader_eof_total 12678
telemt_me_idle_close_by_peer_total 12678
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 146168
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378840
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 815
telemt_desync_full_logged_total 327
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 289
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 12073
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11914
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 378510
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 4580017304 (4.27 GB)
telemt_user_octets_to_client{user="hello"} 102224605984 (95.20 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 49703.8 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515845
telemt_connections_bad_total 5824
telemt_handshake_timeouts_total 3204
telemt_upstream_connect_attempt_total 14468
telemt_upstream_connect_success_total 14407
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 14468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6899
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 549
telemt_me_reconnect_attempts_total 15628
telemt_me_reconnect_success_total 11846
telemt_me_reader_eof_total 12504
telemt_me_idle_close_by_peer_total 12504
telemt_me_route_drop_no_conn_total 166755
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 469523
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2377
telemt_desync_full_logged_total 928
telemt_desync_suppressed_total 1449
telemt_desync_frames_bucket_total{bucket="1_2"} 879
telemt_desync_frames_bucket_total{bucket="3_10"} 1007
telemt_desync_frames_bucket_total{bucket="gt_10"} 491
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 12115
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11846
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 469147
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 8721421632 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 166648734128 (155.20 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 54
```