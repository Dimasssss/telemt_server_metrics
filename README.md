# Server Metrics 2026-03-11 10:51:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 73466.1 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1626294
telemt_connections_bad_total 24861
telemt_handshake_timeouts_total 42332
telemt_upstream_connect_attempt_total 15221
telemt_upstream_connect_success_total 15212
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 804
telemt_me_reconnect_attempts_total 23198
telemt_me_reconnect_success_total 11504
telemt_me_reader_eof_total 12437
telemt_me_idle_close_by_peer_total 12437
telemt_me_route_drop_no_conn_total 599378
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1478090
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7518
telemt_desync_full_logged_total 2051
telemt_desync_suppressed_total 5467
telemt_desync_frames_bucket_total{bucket="1_2"} 1959
telemt_desync_frames_bucket_total{bucket="3_10"} 2844
telemt_desync_frames_bucket_total{bucket="gt_10"} 2715
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11982
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11498
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 478
telemt_user_connections_total{user="hello"} 1476670
telemt_user_connections_current{user="hello"} 1252
telemt_user_octets_from_client{user="hello"} 19099991396 (17.79 GB)
telemt_user_octets_to_client{user="hello"} 422135849276 (393.14 GB)
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 73522.9 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 621237
telemt_connections_bad_total 10399
telemt_handshake_timeouts_total 38753
telemt_upstream_connect_attempt_total 24319
telemt_upstream_connect_success_total 21386
telemt_upstream_connect_fail_total 2933
telemt_upstream_connect_attempts_per_request{bucket="1"} 24319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2933
telemt_me_keepalive_timeout_total 2159
telemt_me_reconnect_attempts_total 15608
telemt_me_reconnect_success_total 14763
telemt_me_reader_eof_total 15631
telemt_me_idle_close_by_peer_total 15629
telemt_me_route_drop_no_conn_total 253508
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 525847
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2393
telemt_desync_full_logged_total 749
telemt_desync_suppressed_total 1644
telemt_desync_frames_bucket_total{bucket="1_2"} 788
telemt_desync_frames_bucket_total{bucket="3_10"} 859
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 14945
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14741
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 528073
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 5298517326 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 147593313612 (137.46 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 73522.6 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1077109
telemt_connections_bad_total 7726
telemt_handshake_timeouts_total 104071
telemt_upstream_connect_attempt_total 19801
telemt_upstream_connect_success_total 19557
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 19801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 812
telemt_me_reconnect_attempts_total 28420
telemt_me_reconnect_success_total 14798
telemt_me_reader_eof_total 15904
telemt_me_idle_close_by_peer_total 15904
telemt_me_route_drop_no_conn_total 357146
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 924645
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2586
telemt_desync_full_logged_total 766
telemt_desync_suppressed_total 1820
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 963
telemt_desync_frames_bucket_total{bucket="gt_10"} 1009
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 15412
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 14787
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 614
telemt_user_connections_total{user="hello"} 925475
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 10887107133 (10.14 GB)
telemt_user_octets_to_client{user="hello"} 282261690617 (262.88 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 73523.2 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784153
telemt_connections_bad_total 69129
telemt_handshake_timeouts_total 74080
telemt_upstream_connect_attempt_total 20070
telemt_upstream_connect_success_total 20070
telemt_upstream_connect_attempts_per_request{bucket="1"} 20070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 773
telemt_me_reconnect_attempts_total 17464
telemt_me_reconnect_success_total 16405
telemt_me_reader_eof_total 17412
telemt_me_idle_close_by_peer_total 17411
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 247566
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618125
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1370
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 844
telemt_desync_frames_bucket_total{bucket="1_2"} 477
telemt_desync_frames_bucket_total{bucket="3_10"} 505
telemt_desync_frames_bucket_total{bucket="gt_10"} 388
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16600
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16380
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 617495
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 7102814800 (6.62 GB)
telemt_user_octets_to_client{user="hello"} 176619380364 (164.49 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 73522.9 (20h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 837741
telemt_connections_bad_total 6086
telemt_handshake_timeouts_total 7913
telemt_upstream_connect_attempt_total 19806
telemt_upstream_connect_success_total 19723
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 19806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 819
telemt_me_reconnect_attempts_total 19737
telemt_me_reconnect_success_total 15940
telemt_me_reader_eof_total 16834
telemt_me_idle_close_by_peer_total 16834
telemt_me_route_drop_no_conn_total 291579
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 760085
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3152
telemt_desync_full_logged_total 1175
telemt_desync_suppressed_total 1977
telemt_desync_frames_bucket_total{bucket="1_2"} 1080
telemt_desync_frames_bucket_total{bucket="3_10"} 1265
telemt_desync_frames_bucket_total{bucket="gt_10"} 807
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16256
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15940
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 759825
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 11523900931 (10.73 GB)
telemt_user_octets_to_client{user="hello"} 278594106138 (259.46 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 93
```