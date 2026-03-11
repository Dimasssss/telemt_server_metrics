# Server Metrics 2026-03-11 17:19:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 96750.9 (26h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2435193
telemt_connections_bad_total 45782
telemt_handshake_timeouts_total 54530
telemt_upstream_connect_attempt_total 20362
telemt_upstream_connect_success_total 20350
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5108
telemt_me_reconnect_attempts_total 33325
telemt_me_reconnect_success_total 15448
telemt_me_reader_eof_total 16736
telemt_me_idle_close_by_peer_total 16736
telemt_me_route_drop_no_conn_total 905396
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2226348
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11462
telemt_desync_full_logged_total 3147
telemt_desync_suppressed_total 8315
telemt_desync_frames_bucket_total{bucket="1_2"} 2827
telemt_desync_frames_bucket_total{bucket="3_10"} 4427
telemt_desync_frames_bucket_total{bucket="gt_10"} 4208
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 16178
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15442
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 730
telemt_user_connections_total{user="hello"} 2224795
telemt_user_connections_current{user="hello"} 1272
telemt_user_octets_from_client{user="hello"} 30140302700 (28.07 GB)
telemt_user_octets_to_client{user="hello"} 627031052640 (583.97 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 96807.6 (26h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 912718
telemt_connections_bad_total 16152
telemt_handshake_timeouts_total 76741
telemt_upstream_connect_attempt_total 30488
telemt_upstream_connect_success_total 27527
telemt_upstream_connect_fail_total 2961
telemt_upstream_connect_attempts_per_request{bucket="1"} 30488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2961
telemt_me_keepalive_timeout_total 2669
telemt_me_reconnect_attempts_total 21811
telemt_me_reconnect_success_total 19707
telemt_me_reader_eof_total 20843
telemt_me_idle_close_by_peer_total 20840
telemt_me_route_drop_no_conn_total 347528
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 763938
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3036
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 2069
telemt_desync_frames_bucket_total{bucket="1_2"} 920
telemt_desync_frames_bucket_total{bucket="3_10"} 1090
telemt_desync_frames_bucket_total{bucket="gt_10"} 1026
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19982
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19684
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 766399
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 9008757398 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 216743114892 (201.86 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 96807.5 (26h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1560984
telemt_connections_bad_total 9538
telemt_handshake_timeouts_total 126817
telemt_upstream_connect_attempt_total 25120
telemt_upstream_connect_success_total 24799
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 25120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1771
telemt_me_reconnect_attempts_total 43488
telemt_me_reconnect_success_total 18830
telemt_me_reader_eof_total 20426
telemt_me_idle_close_by_peer_total 20426
telemt_me_route_drop_no_conn_total 569114
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1364509
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3598
telemt_desync_full_logged_total 1054
telemt_desync_suppressed_total 2544
telemt_desync_frames_bucket_total{bucket="1_2"} 878
telemt_desync_frames_bucket_total{bucket="3_10"} 1360
telemt_desync_frames_bucket_total{bucket="gt_10"} 1360
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19861
telemt_me_refill_failed_total 765
telemt_me_writer_restored_same_endpoint_total 18818
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1031
telemt_user_connections_total{user="hello"} 1364201
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 16805837477 (15.65 GB)
telemt_user_octets_to_client{user="hello"} 414231809713 (385.78 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 96808.0 (26h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1118773
telemt_connections_bad_total 77987
telemt_handshake_timeouts_total 106215
telemt_upstream_connect_attempt_total 26070
telemt_upstream_connect_success_total 26070
telemt_upstream_connect_attempts_per_request{bucket="1"} 26070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1188
telemt_me_reconnect_attempts_total 23369
telemt_me_reconnect_success_total 21232
telemt_me_reader_eof_total 22513
telemt_me_idle_close_by_peer_total 22512
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 369494
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 901174
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1894
telemt_desync_full_logged_total 720
telemt_desync_suppressed_total 1174
telemt_desync_frames_bucket_total{bucket="1_2"} 677
telemt_desync_frames_bucket_total{bucket="3_10"} 669
telemt_desync_frames_bucket_total{bucket="gt_10"} 548
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21525
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 21200
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 900452
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 10804541436 (10.06 GB)
telemt_user_octets_to_client{user="hello"} 274227694228 (255.39 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1484.2 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28608
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 167
telemt_upstream_connect_attempt_total 347
telemt_upstream_connect_success_total 347
telemt_upstream_connect_attempts_per_request{bucket="1"} 347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 233
telemt_me_reconnect_success_total 232
telemt_me_reader_eof_total 195
telemt_me_idle_close_by_peer_total 195
telemt_me_route_drop_no_conn_total 8521
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26515
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_me_writer_removed_unexpected_total 218
telemt_me_writer_restored_same_endpoint_total 210
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_user_connections_total{user="hello"} 26516
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 231750632 (221.01 MB)
telemt_user_octets_to_client{user="hello"} 7384847936 (6.88 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 101
```