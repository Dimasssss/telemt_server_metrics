# Server Metrics 2026-03-11 01:57:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 41418.8 (11h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 826945
telemt_connections_bad_total 9536
telemt_handshake_timeouts_total 11458
telemt_upstream_connect_attempt_total 8975
telemt_upstream_connect_success_total 8966
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 489
telemt_me_reconnect_attempts_total 18518
telemt_me_reconnect_success_total 6851
telemt_me_reader_eof_total 7491
telemt_me_idle_close_by_peer_total 7491
telemt_me_route_drop_no_conn_total 336128
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 781776
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3640
telemt_desync_full_logged_total 1024
telemt_desync_suppressed_total 2616
telemt_desync_frames_bucket_total{bucket="1_2"} 1063
telemt_desync_frames_bucket_total{bucket="3_10"} 1360
telemt_desync_frames_bucket_total{bucket="gt_10"} 1217
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7272
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6845
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 781516
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 10671219348 (9.94 GB)
telemt_user_octets_to_client{user="hello"} 236538835056 (220.29 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 41475.6 (11h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354663
telemt_connections_bad_total 2407
telemt_handshake_timeouts_total 18023
telemt_upstream_connect_attempt_total 16358
telemt_upstream_connect_success_total 13470
telemt_upstream_connect_fail_total 2888
telemt_upstream_connect_attempts_per_request{bucket="1"} 16358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2888
telemt_me_keepalive_timeout_total 1727
telemt_me_reconnect_attempts_total 9229
telemt_me_reconnect_success_total 8412
telemt_me_reader_eof_total 8882
telemt_me_idle_close_by_peer_total 8880
telemt_me_route_drop_no_conn_total 175545
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303412
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1787
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 8521
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 8391
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 305682
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 2878974186 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 72112114268 (67.16 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 41475.1 (11h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590641
telemt_connections_bad_total 4889
telemt_handshake_timeouts_total 34353
telemt_upstream_connect_attempt_total 11362
telemt_upstream_connect_success_total 11206
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 11362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 525
telemt_me_reconnect_attempts_total 19086
telemt_me_reconnect_success_total 8021
telemt_me_reader_eof_total 8710
telemt_me_idle_close_by_peer_total 8710
telemt_me_route_drop_no_conn_total 201058
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 522702
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1526
telemt_desync_full_logged_total 439
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 525
telemt_desync_frames_bucket_total{bucket="gt_10"} 657
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 8477
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8010
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 456
telemt_user_connections_total{user="hello"} 523612
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 6957935829 (6.48 GB)
telemt_user_octets_to_client{user="hello"} 159673749317 (148.71 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 41475.7 (11h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439017
telemt_connections_bad_total 39329
telemt_handshake_timeouts_total 42230
telemt_upstream_connect_attempt_total 12014
telemt_upstream_connect_success_total 12014
telemt_upstream_connect_attempts_per_request{bucket="1"} 12014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 426
telemt_me_reconnect_attempts_total 10935
telemt_me_reconnect_success_total 9900
telemt_me_reader_eof_total 10483
telemt_me_idle_close_by_peer_total 10483
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 132456
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 343958
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 737
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 443
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 10023
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9882
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 343628
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 4270734536 (3.98 GB)
telemt_user_octets_to_client{user="hello"} 92754253228 (86.38 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 41475.2 (11h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463409
telemt_connections_bad_total 5338
telemt_handshake_timeouts_total 2978
telemt_upstream_connect_attempt_total 12308
telemt_upstream_connect_success_total 12256
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 12308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 520
telemt_me_reconnect_attempts_total 13879
telemt_me_reconnect_success_total 10108
telemt_me_reader_eof_total 10644
telemt_me_idle_close_by_peer_total 10644
telemt_me_route_drop_no_conn_total 151590
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423916
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2296
telemt_desync_full_logged_total 892
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 850
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 10356
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10108
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 423599
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 8441487392 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 150592154476 (140.25 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 29
```