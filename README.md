# Server Metrics 2026-03-14 11:47:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 193710.4 (53h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5601384
telemt_connections_bad_total 58691
telemt_handshake_timeouts_total 123559
telemt_upstream_connect_attempt_total 40588
telemt_upstream_connect_success_total 40328
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 40588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 7841
telemt_me_reconnect_attempts_total 44713
telemt_me_reconnect_success_total 28342
telemt_me_reader_eof_total 30518
telemt_me_idle_close_by_peer_total 30517
telemt_me_route_drop_no_conn_total 2119249
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5137624
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19741
telemt_desync_full_logged_total 5395
telemt_desync_suppressed_total 14346
telemt_desync_frames_bucket_total{bucket="1_2"} 4784
telemt_desync_frames_bucket_total{bucket="3_10"} 7528
telemt_desync_frames_bucket_total{bucket="gt_10"} 7429
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29267
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28329
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 925
telemt_user_connections_total{user="hello"} 5139051
telemt_user_connections_current{user="hello"} 1709
telemt_user_octets_from_client{user="hello"} 79605169412 (74.14 GB)
telemt_user_octets_to_client{user="hello"} 1636235512545 (1.49 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 93374.2 (25h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1069894
telemt_connections_bad_total 58887
telemt_handshake_timeouts_total 24540
telemt_upstream_connect_attempt_total 24289
telemt_upstream_connect_success_total 23991
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 24289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 2388
telemt_me_reconnect_attempts_total 32319
telemt_me_reconnect_success_total 17319
telemt_me_reader_eof_total 18678
telemt_me_idle_close_by_peer_total 18677
telemt_me_route_drop_no_conn_total 360648
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879458
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2444
telemt_desync_full_logged_total 768
telemt_desync_suppressed_total 1676
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 1020
telemt_desync_frames_bucket_total{bucket="gt_10"} 803
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18033
telemt_me_refill_failed_total 462
telemt_me_writer_restored_same_endpoint_total 17311
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 714
telemt_user_connections_total{user="hello"} 881373
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 9644786805 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 310801778648 (289.46 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 223331.2 (62h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3971821
telemt_connections_bad_total 46189
telemt_handshake_timeouts_total 268400
telemt_upstream_connect_attempt_total 50384
telemt_upstream_connect_success_total 50363
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11253
telemt_me_reconnect_attempts_total 44901
telemt_me_reconnect_success_total 38900
telemt_me_reader_eof_total 41317
telemt_me_idle_close_by_peer_total 41315
telemt_me_route_drop_no_conn_total 1364564
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3322123
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10705
telemt_desync_full_logged_total 3617
telemt_desync_suppressed_total 7088
telemt_desync_frames_bucket_total{bucket="1_2"} 1949
telemt_desync_frames_bucket_total{bucket="3_10"} 3872
telemt_desync_frames_bucket_total{bucket="gt_10"} 4884
telemt_pool_swap_total 207
telemt_pool_stale_pick_total 4
telemt_me_writer_removed_unexpected_total 39476
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38859
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 576
telemt_user_connections_total{user="hello"} 3321266
telemt_user_connections_current{user="hello"} 1082
telemt_user_octets_from_client{user="hello"} 56374845764 (52.50 GB)
telemt_user_octets_to_client{user="hello"} 1189684108405 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 223333.5 (62h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2601875
telemt_connections_bad_total 23506
telemt_handshake_timeouts_total 333836
telemt_upstream_connect_attempt_total 69004
telemt_upstream_connect_success_total 66497
telemt_upstream_connect_fail_total 2370
telemt_upstream_connect_attempts_per_request{bucket="1"} 68730
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2369
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20959
telemt_me_reconnect_attempts_total 61111
telemt_me_reconnect_success_total 48331
telemt_me_reader_eof_total 51792
telemt_me_idle_close_by_peer_total 51784
telemt_me_route_drop_no_conn_total 865085
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2034894
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4112
telemt_desync_full_logged_total 1352
telemt_desync_suppressed_total 2760
telemt_desync_frames_bucket_total{bucket="1_2"} 1169
telemt_desync_frames_bucket_total{bucket="3_10"} 1680
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 49152
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48306
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 821
telemt_user_connections_total{user="hello"} 2041274
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 30262701887 (28.18 GB)
telemt_user_octets_to_client{user="hello"} 729153266834 (679.08 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 92767.1 (25h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1055063
telemt_connections_bad_total 18086
telemt_handshake_timeouts_total 13719
telemt_upstream_connect_attempt_total 22702
telemt_upstream_connect_success_total 22079
telemt_upstream_connect_fail_total 622
telemt_upstream_connect_attempts_per_request{bucket="1"} 22701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 622
telemt_me_keepalive_timeout_total 1788
telemt_me_reconnect_attempts_total 81150
telemt_me_reconnect_success_total 17456
telemt_me_reader_eof_total 19854
telemt_me_idle_close_by_peer_total 19853
telemt_me_route_drop_no_conn_total 426923
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 976618
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2623
telemt_desync_full_logged_total 820
telemt_desync_suppressed_total 1803
telemt_desync_frames_bucket_total{bucket="1_2"} 934
telemt_desync_frames_bucket_total{bucket="3_10"} 938
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19605
telemt_me_refill_failed_total 1985
telemt_me_writer_restored_same_endpoint_total 17451
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2149
telemt_user_connections_total{user="hello"} 975827
telemt_user_connections_current{user="hello"} 702
telemt_user_octets_from_client{user="hello"} 17044272252 (15.87 GB)
telemt_user_octets_to_client{user="hello"} 328992090860 (306.40 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 94
```