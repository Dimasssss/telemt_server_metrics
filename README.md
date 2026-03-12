# Server Metrics 2026-03-12 18:04:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 43533.6 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1566344
telemt_connections_bad_total 20416
telemt_handshake_timeouts_total 14652
telemt_upstream_connect_attempt_total 8663
telemt_upstream_connect_success_total 8612
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 531
telemt_me_reconnect_attempts_total 15226
telemt_me_reconnect_success_total 6381
telemt_me_reader_eof_total 6910
telemt_me_idle_close_by_peer_total 6909
telemt_me_route_drop_no_conn_total 610830
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1467322
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7489
telemt_desync_full_logged_total 1902
telemt_desync_suppressed_total 5587
telemt_desync_frames_bucket_total{bucket="1_2"} 1939
telemt_desync_frames_bucket_total{bucket="3_10"} 2724
telemt_desync_frames_bucket_total{bucket="gt_10"} 2826
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6747
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6368
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 1466812
telemt_user_connections_current{user="hello"} 1619
telemt_user_octets_from_client{user="hello"} 22358452916 (20.82 GB)
telemt_user_octets_to_client{user="hello"} 482750010400 (449.60 GB)
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 73154.2 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 677231
telemt_connections_bad_total 8712
telemt_handshake_timeouts_total 29239
telemt_upstream_connect_attempt_total 18808
telemt_upstream_connect_success_total 18779
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 18808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3328
telemt_me_reconnect_attempts_total 13528
telemt_me_reconnect_success_total 13443
telemt_me_reader_eof_total 14287
telemt_me_idle_close_by_peer_total 14287
telemt_me_route_drop_no_conn_total 215431
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 608803
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2615
telemt_desync_full_logged_total 801
telemt_desync_suppressed_total 1814
telemt_desync_frames_bucket_total{bucket="1_2"} 1077
telemt_desync_frames_bucket_total{bucket="3_10"} 857
telemt_desync_frames_bucket_total{bucket="gt_10"} 681
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 13584
telemt_me_writer_restored_same_endpoint_total 13434
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 610683
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 9232014672 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 230015910987 (214.22 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 73154.1 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1407935
telemt_connections_bad_total 6884
telemt_handshake_timeouts_total 98966
telemt_upstream_connect_attempt_total 17386
telemt_upstream_connect_success_total 17381
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1141
telemt_me_reconnect_attempts_total 14577
telemt_me_reconnect_success_total 13335
telemt_me_reader_eof_total 14061
telemt_me_idle_close_by_peer_total 14060
telemt_me_route_drop_no_conn_total 460395
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1071501
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4511
telemt_desync_full_logged_total 1400
telemt_desync_suppressed_total 3111
telemt_desync_frames_bucket_total{bucket="1_2"} 695
telemt_desync_frames_bucket_total{bucket="3_10"} 1642
telemt_desync_frames_bucket_total{bucket="gt_10"} 2174
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13448
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13294
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 1071363
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 16111527768 (15.01 GB)
telemt_user_octets_to_client{user="hello"} 383920406849 (357.55 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 73154.7 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 852334
telemt_connections_bad_total 10856
telemt_handshake_timeouts_total 64381
telemt_upstream_connect_attempt_total 19092
telemt_upstream_connect_success_total 19017
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 19092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1608
telemt_me_reconnect_attempts_total 23055
telemt_me_reconnect_success_total 15336
telemt_me_reader_eof_total 16377
telemt_me_idle_close_by_peer_total 16377
telemt_me_route_drop_no_conn_total 298901
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738627
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1692
telemt_desync_full_logged_total 565
telemt_desync_suppressed_total 1127
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 655
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15698
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15315
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 738042
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 9053563736 (8.43 GB)
telemt_user_octets_to_client{user="hello"} 297468210784 (277.04 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 73154.6 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 959287
telemt_connections_bad_total 11403
telemt_handshake_timeouts_total 7818
telemt_upstream_connect_attempt_total 23267
telemt_upstream_connect_success_total 22991
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 23267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_keepalive_timeout_total 1323
telemt_me_reconnect_attempts_total 30322
telemt_me_reconnect_success_total 19291
telemt_me_reader_eof_total 20275
telemt_me_idle_close_by_peer_total 20275
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 355205
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 881049
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3410
telemt_desync_full_logged_total 1179
telemt_desync_suppressed_total 2231
telemt_desync_frames_bucket_total{bucket="1_2"} 948
telemt_desync_frames_bucket_total{bucket="3_10"} 1155
telemt_desync_frames_bucket_total{bucket="gt_10"} 1307
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 19852
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19247
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 880929
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 10775488368 (10.04 GB)
telemt_user_octets_to_client{user="hello"} 280360384912 (261.11 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 102
```