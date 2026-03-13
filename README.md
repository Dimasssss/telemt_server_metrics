# Server Metrics 2026-03-13 19:51:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 136345.9 (37h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4350114
telemt_connections_bad_total 37800
telemt_handshake_timeouts_total 105722
telemt_upstream_connect_attempt_total 28597
telemt_upstream_connect_success_total 28403
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 28597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 6531
telemt_me_reconnect_attempts_total 29375
telemt_me_reconnect_success_total 19259
telemt_me_reader_eof_total 20665
telemt_me_idle_close_by_peer_total 20664
telemt_me_route_drop_no_conn_total 1635283
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3979587
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15702
telemt_desync_full_logged_total 4185
telemt_desync_suppressed_total 11517
telemt_desync_frames_bucket_total{bucket="1_2"} 3910
telemt_desync_frames_bucket_total{bucket="3_10"} 5986
telemt_desync_frames_bucket_total{bucket="gt_10"} 5806
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 19852
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19246
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 593
telemt_user_connections_total{user="hello"} 3981748
telemt_user_connections_current{user="hello"} 1534
telemt_user_octets_from_client{user="hello"} 57717784864 (53.75 GB)
telemt_user_octets_to_client{user="hello"} 1255509347357 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 36009.5 (10h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519203
telemt_connections_bad_total 40343
telemt_handshake_timeouts_total 11843
telemt_upstream_connect_attempt_total 10455
telemt_upstream_connect_success_total 10241
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 10455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 1870
telemt_me_reconnect_attempts_total 9831
telemt_me_reconnect_success_total 6416
telemt_me_reader_eof_total 6784
telemt_me_idle_close_by_peer_total 6783
telemt_me_route_drop_no_conn_total 194382
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450536
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1545
telemt_desync_full_logged_total 416
telemt_desync_suppressed_total 1129
telemt_desync_frames_bucket_total{bucket="1_2"} 328
telemt_desync_frames_bucket_total{bucket="3_10"} 684
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 6610
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6408
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 452466
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 4842693805 (4.51 GB)
telemt_user_octets_to_client{user="hello"} 142820228000 (133.01 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 165966.2 (46h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3174668
telemt_connections_bad_total 29304
telemt_handshake_timeouts_total 213180
telemt_upstream_connect_attempt_total 36812
telemt_upstream_connect_success_total 36796
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 36812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 10186
telemt_me_reconnect_attempts_total 30771
telemt_me_reconnect_success_total 28205
telemt_me_reader_eof_total 29896
telemt_me_idle_close_by_peer_total 29895
telemt_me_route_drop_no_conn_total 1086138
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2627178
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8748
telemt_desync_full_logged_total 2905
telemt_desync_suppressed_total 5843
telemt_desync_frames_bucket_total{bucket="1_2"} 1439
telemt_desync_frames_bucket_total{bucket="3_10"} 3203
telemt_desync_frames_bucket_total{bucket="gt_10"} 4106
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 28543
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28164
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 2626460
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 43467394368 (40.48 GB)
telemt_user_octets_to_client{user="hello"} 924496800209 (861.00 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 165966.9 (46h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2050447
telemt_connections_bad_total 22122
telemt_handshake_timeouts_total 189669
telemt_upstream_connect_attempt_total 52070
telemt_upstream_connect_success_total 49634
telemt_upstream_connect_fail_total 2299
telemt_upstream_connect_attempts_per_request{bucket="1"} 51796
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2298
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20187
telemt_me_reconnect_attempts_total 43343
telemt_me_reconnect_success_total 34336
telemt_me_reader_eof_total 36865
telemt_me_idle_close_by_peer_total 36858
telemt_me_route_drop_no_conn_total 726437
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1692583
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3645
telemt_desync_full_logged_total 1161
telemt_desync_suppressed_total 2484
telemt_desync_frames_bucket_total{bucket="1_2"} 960
telemt_desync_frames_bucket_total{bucket="3_10"} 1515
telemt_desync_frames_bucket_total{bucket="gt_10"} 1170
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 34907
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34312
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 571
telemt_user_connections_total{user="hello"} 1698452
telemt_user_connections_current{user="hello"} 569
telemt_user_octets_from_client{user="hello"} 26008114863 (24.22 GB)
telemt_user_octets_to_client{user="hello"} 639455232154 (595.54 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 35402.2 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558755
telemt_connections_bad_total 5700
telemt_handshake_timeouts_total 5448
telemt_upstream_connect_attempt_total 7673
telemt_upstream_connect_success_total 7421
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 7673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 960
telemt_me_reconnect_attempts_total 26559
telemt_me_reconnect_success_total 5622
telemt_me_reader_eof_total 6385
telemt_me_idle_close_by_peer_total 6384
telemt_me_route_drop_no_conn_total 211933
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 523627
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1456
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 583
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6321
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5618
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 699
telemt_user_connections_total{user="hello"} 523591
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 6105357288 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 167519352736 (156.01 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 76
```