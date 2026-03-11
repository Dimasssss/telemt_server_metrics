# Server Metrics 2026-03-11 07:32:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 61541.0 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1238571
telemt_connections_bad_total 13655
telemt_handshake_timeouts_total 39167
telemt_upstream_connect_attempt_total 12858
telemt_upstream_connect_success_total 12849
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 716
telemt_me_reconnect_attempts_total 21409
telemt_me_reconnect_success_total 9725
telemt_me_reader_eof_total 10568
telemt_me_idle_close_by_peer_total 10568
telemt_me_route_drop_no_conn_total 456633
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1118597
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5467
telemt_desync_full_logged_total 1528
telemt_desync_suppressed_total 3939
telemt_desync_frames_bucket_total{bucket="1_2"} 1447
telemt_desync_frames_bucket_total{bucket="3_10"} 2062
telemt_desync_frames_bucket_total{bucket="gt_10"} 1958
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 10187
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9719
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 1118260
telemt_user_connections_current{user="hello"} 1237
telemt_user_octets_from_client{user="hello"} 14851590292 (13.83 GB)
telemt_user_octets_to_client{user="hello"} 329878221112 (307.22 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 61597.9 (17h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478917
telemt_connections_bad_total 7127
telemt_handshake_timeouts_total 23108
telemt_upstream_connect_attempt_total 21724
telemt_upstream_connect_success_total 18807
telemt_upstream_connect_fail_total 2917
telemt_upstream_connect_attempts_per_request{bucket="1"} 21724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2917
telemt_me_keepalive_timeout_total 2044
telemt_me_reconnect_attempts_total 13594
telemt_me_reconnect_success_total 12768
telemt_me_reader_eof_total 13507
telemt_me_idle_close_by_peer_total 13505
telemt_me_route_drop_no_conn_total 210425
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409079
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2046
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1416
telemt_desync_frames_bucket_total{bucket="1_2"} 667
telemt_desync_frames_bucket_total{bucket="3_10"} 737
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12914
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12746
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 411347
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 4030446938 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 108335606044 (100.90 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 61597.7 (17h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808928
telemt_connections_bad_total 6875
telemt_handshake_timeouts_total 43690
telemt_upstream_connect_attempt_total 16692
telemt_upstream_connect_success_total 16486
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 16692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 734
telemt_me_reconnect_attempts_total 24673
telemt_me_reconnect_success_total 12318
telemt_me_reader_eof_total 13279
telemt_me_idle_close_by_peer_total 13279
telemt_me_route_drop_no_conn_total 274301
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 723696
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2103
telemt_desync_full_logged_total 616
telemt_desync_suppressed_total 1487
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 847
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 12860
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12307
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 724490
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 8515826201 (7.93 GB)
telemt_user_octets_to_client{user="hello"} 213928280469 (199.24 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 61598.1 (17h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618452
telemt_connections_bad_total 57699
telemt_handshake_timeouts_total 61182
telemt_upstream_connect_attempt_total 17336
telemt_upstream_connect_success_total 17336
telemt_upstream_connect_attempts_per_request{bucket="1"} 17336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 662
telemt_me_reconnect_attempts_total 15296
telemt_me_reconnect_success_total 14246
telemt_me_reader_eof_total 15132
telemt_me_idle_close_by_peer_total 15131
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 189458
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479096
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1094
telemt_desync_full_logged_total 428
telemt_desync_suppressed_total 666
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 412
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 14413
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14224
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 478511
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 5690338288 (5.30 GB)
telemt_user_octets_to_client{user="hello"} 130953278980 (121.96 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 61597.7 (17h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 645833
telemt_connections_bad_total 5969
telemt_handshake_timeouts_total 4659
telemt_upstream_connect_attempt_total 17188
telemt_upstream_connect_success_total 17118
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 17188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 689
telemt_me_reconnect_attempts_total 17701
telemt_me_reconnect_success_total 13915
telemt_me_reader_eof_total 14705
telemt_me_idle_close_by_peer_total 14705
telemt_me_route_drop_no_conn_total 215525
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588433
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2742
telemt_desync_full_logged_total 1034
telemt_desync_suppressed_total 1708
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1146
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 14210
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13915
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 588146
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 9992937571 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 215566737558 (200.76 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 122
```