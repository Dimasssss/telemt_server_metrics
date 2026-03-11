# Server Metrics 2026-03-11 15:57:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 91848.9 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2274703
telemt_connections_bad_total 39521
telemt_handshake_timeouts_total 53471
telemt_upstream_connect_attempt_total 19175
telemt_upstream_connect_success_total 19162
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4895
telemt_me_reconnect_attempts_total 32393
telemt_me_reconnect_success_total 14524
telemt_me_reader_eof_total 15760
telemt_me_idle_close_by_peer_total 15760
telemt_me_route_drop_no_conn_total 843185
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2080262
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10842
telemt_desync_full_logged_total 2950
telemt_desync_suppressed_total 7892
telemt_desync_frames_bucket_total{bucket="1_2"} 2684
telemt_desync_frames_bucket_total{bucket="3_10"} 4179
telemt_desync_frames_bucket_total{bucket="gt_10"} 3979
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 15242
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14518
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 2078702
telemt_user_connections_current{user="hello"} 1314
telemt_user_octets_from_client{user="hello"} 27828324896 (25.92 GB)
telemt_user_octets_to_client{user="hello"} 588513086452 (548.10 GB)
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 91905.7 (25h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 842882
telemt_connections_bad_total 14221
telemt_handshake_timeouts_total 58292
telemt_upstream_connect_attempt_total 29116
telemt_upstream_connect_success_total 26158
telemt_upstream_connect_fail_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 29116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2958
telemt_me_keepalive_timeout_total 2560
telemt_me_reconnect_attempts_total 20667
telemt_me_reconnect_success_total 18574
telemt_me_reader_eof_total 19665
telemt_me_idle_close_by_peer_total 19662
telemt_me_route_drop_no_conn_total 329353
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715797
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2924
telemt_desync_full_logged_total 932
telemt_desync_suppressed_total 1992
telemt_desync_frames_bucket_total{bucket="1_2"} 903
telemt_desync_frames_bucket_total{bucket="3_10"} 1049
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 18841
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18551
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 718257
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 8283315522 (7.71 GB)
telemt_user_octets_to_client{user="hello"} 203724380844 (189.73 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 91905.5 (25h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1458386
telemt_connections_bad_total 8687
telemt_handshake_timeouts_total 124686
telemt_upstream_connect_attempt_total 24024
telemt_upstream_connect_success_total 23723
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 24024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 1591
telemt_me_reconnect_attempts_total 39049
telemt_me_reconnect_success_total 18005
telemt_me_reader_eof_total 19468
telemt_me_idle_close_by_peer_total 19468
telemt_me_route_drop_no_conn_total 532191
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1272142
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3359
telemt_desync_full_logged_total 995
telemt_desync_suppressed_total 2364
telemt_desync_frames_bucket_total{bucket="1_2"} 827
telemt_desync_frames_bucket_total{bucket="3_10"} 1271
telemt_desync_frames_bucket_total{bucket="gt_10"} 1261
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18907
telemt_me_refill_failed_total 653
telemt_me_writer_restored_same_endpoint_total 17994
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 1271851
telemt_user_connections_current{user="hello"} 815
telemt_user_octets_from_client{user="hello"} 15308118913 (14.26 GB)
telemt_user_octets_to_client{user="hello"} 384406612317 (358.01 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 91906.1 (25h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1048699
telemt_connections_bad_total 77971
telemt_handshake_timeouts_total 102485
telemt_upstream_connect_attempt_total 24721
telemt_upstream_connect_success_total 24721
telemt_upstream_connect_attempts_per_request{bucket="1"} 24721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1016
telemt_me_reconnect_attempts_total 21190
telemt_me_reconnect_success_total 20115
telemt_me_reader_eof_total 21311
telemt_me_idle_close_by_peer_total 21310
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 343385
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 839700
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1755
telemt_desync_full_logged_total 674
telemt_desync_suppressed_total 1081
telemt_desync_frames_bucket_total{bucket="1_2"} 634
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20358
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 20085
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 839019
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 10016932904 (9.33 GB)
telemt_user_octets_to_client{user="hello"} 248028550652 (230.99 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 91905.7 (25h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1159700
telemt_connections_bad_total 6940
telemt_handshake_timeouts_total 11650
telemt_upstream_connect_attempt_total 24953
telemt_upstream_connect_success_total 24840
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 24952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11950
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 1956
telemt_me_reconnect_attempts_total 24191
telemt_me_reconnect_success_total 20100
telemt_me_reader_eof_total 21178
telemt_me_idle_close_by_peer_total 21178
telemt_me_route_drop_no_conn_total 413553
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1055587
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4074
telemt_desync_full_logged_total 1471
telemt_desync_suppressed_total 2603
telemt_desync_frames_bucket_total{bucket="1_2"} 1363
telemt_desync_frames_bucket_total{bucket="3_10"} 1525
telemt_desync_frames_bucket_total{bucket="gt_10"} 1186
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20488
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20100
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 1055291
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 20049493643 (18.67 GB)
telemt_user_octets_to_client{user="hello"} 368567184786 (343.25 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 110
```