# Server Metrics 2026-03-11 04:29:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 50561.7 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 978566
telemt_connections_bad_total 10073
telemt_handshake_timeouts_total 28723
telemt_upstream_connect_attempt_total 10905
telemt_upstream_connect_success_total 10896
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 532
telemt_me_reconnect_attempts_total 19974
telemt_me_reconnect_success_total 8300
telemt_me_reader_eof_total 9045
telemt_me_idle_close_by_peer_total 9045
telemt_me_route_drop_no_conn_total 368432
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 884103
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4016
telemt_desync_full_logged_total 1126
telemt_desync_suppressed_total 2890
telemt_desync_frames_bucket_total{bucket="1_2"} 1132
telemt_desync_frames_bucket_total{bucket="3_10"} 1509
telemt_desync_frames_bucket_total{bucket="gt_10"} 1375
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8740
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8294
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 883821
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 11570886856 (10.78 GB)
telemt_user_octets_to_client{user="hello"} 260521499080 (242.63 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 50618.5 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388341
telemt_connections_bad_total 2532
telemt_handshake_timeouts_total 18875
telemt_upstream_connect_attempt_total 19181
telemt_upstream_connect_success_total 16284
telemt_upstream_connect_fail_total 2897
telemt_upstream_connect_attempts_per_request{bucket="1"} 19181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2897
telemt_me_keepalive_timeout_total 1777
telemt_me_reconnect_attempts_total 11591
telemt_me_reconnect_success_total 10772
telemt_me_reader_eof_total 11385
telemt_me_idle_close_by_peer_total 11383
telemt_me_route_drop_no_conn_total 185552
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333371
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1845
telemt_desync_full_logged_total 547
telemt_desync_suppressed_total 1298
telemt_desync_frames_bucket_total{bucket="1_2"} 569
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 10898
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10751
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 335642
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 3215530122 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 79333431548 (73.89 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 50618.3 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 653709
telemt_connections_bad_total 5547
telemt_handshake_timeouts_total 36072
telemt_upstream_connect_attempt_total 13708
telemt_upstream_connect_success_total 13529
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 13708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 559
telemt_me_reconnect_attempts_total 20960
telemt_me_reconnect_success_total 9890
telemt_me_reader_eof_total 10704
telemt_me_idle_close_by_peer_total 10704
telemt_me_route_drop_no_conn_total 220755
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 582453
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1630
telemt_desync_full_logged_total 482
telemt_desync_suppressed_total 1148
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 573
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 10365
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9879
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 583331
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 7285712561 (6.79 GB)
telemt_user_octets_to_client{user="hello"} 176810658729 (164.67 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 50618.7 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497968
telemt_connections_bad_total 47672
telemt_handshake_timeouts_total 52234
telemt_upstream_connect_attempt_total 14676
telemt_upstream_connect_success_total 14676
telemt_upstream_connect_attempts_per_request{bucket="1"} 14676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 485
telemt_me_reconnect_attempts_total 13157
telemt_me_reconnect_success_total 12116
telemt_me_reader_eof_total 12870
telemt_me_idle_close_by_peer_total 12870
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 148206
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383929
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 820
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 289
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 12258
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12096
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 383597
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 4619075280 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 104606550252 (97.42 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 50618.4 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 522867
telemt_connections_bad_total 5826
telemt_handshake_timeouts_total 3321
telemt_upstream_connect_attempt_total 14726
telemt_upstream_connect_success_total 14664
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 14726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 553
telemt_me_reconnect_attempts_total 15842
telemt_me_reconnect_success_total 12061
telemt_me_reader_eof_total 12733
telemt_me_idle_close_by_peer_total 12733
telemt_me_route_drop_no_conn_total 169219
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476091
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2393
telemt_desync_full_logged_total 935
telemt_desync_suppressed_total 1458
telemt_desync_frames_bucket_total{bucket="1_2"} 882
telemt_desync_frames_bucket_total{bucket="3_10"} 1015
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12333
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12061
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 475712
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 8782831180 (8.18 GB)
telemt_user_octets_to_client{user="hello"} 168758831264 (157.17 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 54
```