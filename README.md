# Server Metrics 2026-03-11 11:01:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 74078.8 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1646633
telemt_connections_bad_total 25365
telemt_handshake_timeouts_total 42928
telemt_upstream_connect_attempt_total 15420
telemt_upstream_connect_success_total 15411
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 806
telemt_me_reconnect_attempts_total 23352
telemt_me_reconnect_success_total 11654
telemt_me_reader_eof_total 12590
telemt_me_idle_close_by_peer_total 12590
telemt_me_route_drop_no_conn_total 606766
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1496706
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7681
telemt_desync_full_logged_total 2090
telemt_desync_suppressed_total 5591
telemt_desync_frames_bucket_total{bucket="1_2"} 1993
telemt_desync_frames_bucket_total{bucket="3_10"} 2903
telemt_desync_frames_bucket_total{bucket="gt_10"} 2785
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 12136
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11648
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 1495287
telemt_user_connections_current{user="hello"} 1297
telemt_user_octets_from_client{user="hello"} 19497048800 (18.16 GB)
telemt_user_octets_to_client{user="hello"} 427198005584 (397.86 GB)
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 74135.5 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 628259
telemt_connections_bad_total 10610
telemt_handshake_timeouts_total 39125
telemt_upstream_connect_attempt_total 24482
telemt_upstream_connect_success_total 21549
telemt_upstream_connect_fail_total 2933
telemt_upstream_connect_attempts_per_request{bucket="1"} 24482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9450
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2933
telemt_me_keepalive_timeout_total 2170
telemt_me_reconnect_attempts_total 15728
telemt_me_reconnect_success_total 14881
telemt_me_reader_eof_total 15764
telemt_me_idle_close_by_peer_total 15762
telemt_me_route_drop_no_conn_total 255931
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 532267
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2435
telemt_desync_full_logged_total 762
telemt_desync_suppressed_total 1673
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 873
telemt_desync_frames_bucket_total{bucket="gt_10"} 764
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 15067
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14859
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 534492
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 5484671234 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 149382072680 (139.12 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 74135.4 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090732
telemt_connections_bad_total 7736
telemt_handshake_timeouts_total 104825
telemt_upstream_connect_attempt_total 19988
telemt_upstream_connect_success_total 19741
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 19988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 813
telemt_me_reconnect_attempts_total 28559
telemt_me_reconnect_success_total 14935
telemt_me_reader_eof_total 16042
telemt_me_idle_close_by_peer_total 16042
telemt_me_route_drop_no_conn_total 362118
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 937328
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2615
telemt_desync_full_logged_total 777
telemt_desync_suppressed_total 1838
telemt_desync_frames_bucket_total{bucket="1_2"} 616
telemt_desync_frames_bucket_total{bucket="3_10"} 981
telemt_desync_frames_bucket_total{bucket="gt_10"} 1018
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 15550
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 14924
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 615
telemt_user_connections_total{user="hello"} 938171
telemt_user_connections_current{user="hello"} 775
telemt_user_octets_from_client{user="hello"} 10969987405 (10.22 GB)
telemt_user_octets_to_client{user="hello"} 285168607485 (265.58 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 74135.8 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 792263
telemt_connections_bad_total 69695
telemt_handshake_timeouts_total 74475
telemt_upstream_connect_attempt_total 20227
telemt_upstream_connect_success_total 20227
telemt_upstream_connect_attempts_per_request{bucket="1"} 20227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 776
telemt_me_reconnect_attempts_total 17577
telemt_me_reconnect_success_total 16518
telemt_me_reader_eof_total 17539
telemt_me_idle_close_by_peer_total 17538
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 250300
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 625186
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1378
telemt_desync_full_logged_total 529
telemt_desync_suppressed_total 849
telemt_desync_frames_bucket_total{bucket="1_2"} 485
telemt_desync_frames_bucket_total{bucket="3_10"} 505
telemt_desync_frames_bucket_total{bucket="gt_10"} 388
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 16714
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16493
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 624554
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 7160911496 (6.67 GB)
telemt_user_octets_to_client{user="hello"} 178455647848 (166.20 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 74135.4 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 848829
telemt_connections_bad_total 6094
telemt_handshake_timeouts_total 8100
telemt_upstream_connect_attempt_total 20058
telemt_upstream_connect_success_total 19974
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 20058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9572
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 832
telemt_me_reconnect_attempts_total 19943
telemt_me_reconnect_success_total 16144
telemt_me_reader_eof_total 17039
telemt_me_idle_close_by_peer_total 17039
telemt_me_route_drop_no_conn_total 295753
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 770064
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3183
telemt_desync_full_logged_total 1183
telemt_desync_suppressed_total 2000
telemt_desync_frames_bucket_total{bucket="1_2"} 1087
telemt_desync_frames_bucket_total{bucket="3_10"} 1276
telemt_desync_frames_bucket_total{bucket="gt_10"} 820
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16462
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 16144
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 769818
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 11609619327 (10.81 GB)
telemt_user_octets_to_client{user="hello"} 280921557450 (261.63 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 122
```