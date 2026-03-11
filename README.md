# Server Metrics 2026-03-11 12:18:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 78672.4 (21h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1804821
telemt_connections_bad_total 25884
telemt_handshake_timeouts_total 46671
telemt_upstream_connect_attempt_total 16364
telemt_upstream_connect_success_total 16355
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 848
telemt_me_reconnect_attempts_total 25198
telemt_me_reconnect_success_total 12372
telemt_me_reader_eof_total 13386
telemt_me_idle_close_by_peer_total 13386
telemt_me_route_drop_no_conn_total 662993
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1645312
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8615
telemt_desync_full_logged_total 2323
telemt_desync_suppressed_total 6292
telemt_desync_frames_bucket_total{bucket="1_2"} 2142
telemt_desync_frames_bucket_total{bucket="3_10"} 3303
telemt_desync_frames_bucket_total{bucket="gt_10"} 3170
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 12904
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12366
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 532
telemt_user_connections_total{user="hello"} 1643855
telemt_user_connections_current{user="hello"} 1455
telemt_user_octets_from_client{user="hello"} 21676340068 (20.19 GB)
telemt_user_octets_to_client{user="hello"} 466060616440 (434.05 GB)
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 78729.1 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688595
telemt_connections_bad_total 12638
telemt_handshake_timeouts_total 49326
telemt_upstream_connect_attempt_total 25723
telemt_upstream_connect_success_total 22782
telemt_upstream_connect_fail_total 2941
telemt_upstream_connect_attempts_per_request{bucket="1"} 25723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2941
telemt_me_keepalive_timeout_total 2427
telemt_me_reconnect_attempts_total 16739
telemt_me_reconnect_success_total 15880
telemt_me_reader_eof_total 16799
telemt_me_idle_close_by_peer_total 16796
telemt_me_route_drop_no_conn_total 272355
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 577495
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2619
telemt_desync_full_logged_total 824
telemt_desync_suppressed_total 1795
telemt_desync_frames_bucket_total{bucket="1_2"} 833
telemt_desync_frames_bucket_total{bucket="3_10"} 957
telemt_desync_frames_bucket_total{bucket="gt_10"} 829
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16083
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15857
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 579715
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 6182340834 (5.76 GB)
telemt_user_octets_to_client{user="hello"} 164965310368 (153.64 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 78729.2 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1188328
telemt_connections_bad_total 7976
telemt_handshake_timeouts_total 111587
telemt_upstream_connect_attempt_total 21115
telemt_upstream_connect_success_total 20860
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 21115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 857
telemt_me_reconnect_attempts_total 29456
telemt_me_reconnect_success_total 15825
telemt_me_reader_eof_total 16983
telemt_me_idle_close_by_peer_total 16983
telemt_me_route_drop_no_conn_total 399082
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1022665
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2729
telemt_desync_full_logged_total 813
telemt_desync_suppressed_total 1916
telemt_desync_frames_bucket_total{bucket="1_2"} 647
telemt_desync_frames_bucket_total{bucket="3_10"} 1025
telemt_desync_frames_bucket_total{bucket="gt_10"} 1057
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16457
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15814
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 1023407
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 11938458401 (11.12 GB)
telemt_user_octets_to_client{user="hello"} 308783674381 (287.58 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 78729.5 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 856088
telemt_connections_bad_total 73882
telemt_handshake_timeouts_total 77567
telemt_upstream_connect_attempt_total 21385
telemt_upstream_connect_success_total 21385
telemt_upstream_connect_attempts_per_request{bucket="1"} 21385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 863
telemt_me_reconnect_attempts_total 18513
telemt_me_reconnect_success_total 17448
telemt_me_reader_eof_total 18503
telemt_me_idle_close_by_peer_total 18502
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 273687
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680322
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1453
telemt_desync_full_logged_total 563
telemt_desync_suppressed_total 890
telemt_desync_frames_bucket_total{bucket="1_2"} 517
telemt_desync_frames_bucket_total{bucket="3_10"} 526
telemt_desync_frames_bucket_total{bucket="gt_10"} 410
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17660
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17421
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 679681
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 7701678388 (7.17 GB)
telemt_user_octets_to_client{user="hello"} 193590811412 (180.30 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 78729.1 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 923977
telemt_connections_bad_total 6255
telemt_handshake_timeouts_total 8759
telemt_upstream_connect_attempt_total 21613
telemt_upstream_connect_success_total 21520
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 21613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10307
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 917
telemt_me_reconnect_attempts_total 21524
telemt_me_reconnect_success_total 17462
telemt_me_reader_eof_total 18429
telemt_me_idle_close_by_peer_total 18429
telemt_me_route_drop_no_conn_total 324597
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 839559
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3455
telemt_desync_full_logged_total 1274
telemt_desync_suppressed_total 2181
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1344
telemt_desync_frames_bucket_total{bucket="gt_10"} 940
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17811
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17462
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 349
telemt_user_connections_total{user="hello"} 839319
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 12441000427 (11.59 GB)
telemt_user_octets_to_client{user="hello"} 303735664222 (282.88 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 109
```